# Cesar-brute-force
#Este proyecto implementa un ataque de fuerza bruta contra el Cifrado César, utilizando Python. El Cifrado César es una técnica de cifrado por sustitución que desplaza cada letra de un mensaje un número fijo de posiciones en el alfabeto.
El objetivo del proyecto es descifrar un texto cifrado mediante una búsqueda exhaustiva de todas las posibles claves de cifrado, detectando automáticamente si el mensaje descifrado está en español.

# Fuerza Bruta con Python sobre el Cifrado César

## Descripción del Proyecto
Este proyecto es una implementación en Python de un ataque de fuerza bruta sobre el **Cifrado César**, un método de cifrado por sustitución que desplaza cada letra del texto cifrado un número fijo de posiciones en el alfabeto.

El objetivo del proyecto es descifrar un texto sin conocer la clave de cifrado mediante la prueba exhaustiva de todas las claves posibles, detectando automáticamente si el resultado es un texto válido en español.

## Características
- Descifrado de textos cifrados mediante ataque de fuerza bruta.
- Detección automática del idioma del texto descifrado utilizando la librería `langdetect`.
- Compatible con Python 3.x.
- Sencillo de usar y fácil de entender para cualquier nivel de programación.

## Tecnologías Utilizadas
- **Python 3.x** - Lenguaje de programación.
- **langdetect** - Librería para detección de idioma.
- **string** - Módulo de Python para manipulación de texto.
- Editor de codigo "emac".

## Requisitos
Antes de ejecutar el script, instala las dependencias necesarias:

```bash
pip install langdetect
sudo apt install emacs -y
emacs "example.py"

