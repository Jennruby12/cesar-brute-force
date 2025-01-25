# Explicación Técnica

El Cifrado César es un cifrado de sustitución simple que desplaza las letras del texto un número fijo de posiciones en el alfabeto.

## Algoritmo de Descifrado

El script de descifrado implementa el siguiente algoritmo:

1. Iterar sobre todas las claves de desplazamiento posibles.
2. Intentar descifrar el texto usando cada clave.
3. Usar la librería `langdetect` para detectar si el texto descifrado es en español.
4. Si el texto descifrado es válido, mostrar el resultado.

**Fragmento de código clave:**

```python
def algoritmo_descifrado(texto_cifrado, clave_descifrado):
    texto_plano = ""
    for letra in texto_cifrado:
        if letra not in ALFABETO:
            texto_plano += letra
        else:
            indice = ALFABETO.index(letra)
            texto_plano += ALFABETO[(indice - clave_descifrado) % len(ALFABETO)]
    return texto_plano
