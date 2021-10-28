# Proyecto-Final-Automatas-Reconocedor-de-Cadenas

## Descripción
Este es un programa en python para construir AFND, AFD, y AFD minimizados a partir de una expresión regular dada, creado como un proyecto de clase para autómatas y lenguajes formales. 

El proyecto realizado se basa en el principio de las expresiones regulares para concordar y reconocer cadenas de caracteres ingresados por un usuario comparándolas con la expresión regular previamente programada. El programa fue desarrollado en ```Python 3.9```.

## Archivos necesarios
- Python: [Descargar Python](https://www.python.org/downloads/)
- Tkinter: Se selecciona durante la instalación de Python
- Librería DFA: ```pip install automata-lib```
- Librería Pillow: ```pip install Pillow```

## Posibles problemas
Debe de estar seguro de tener todos los archivos instalados correctamente.

Es posible que obtenga un error de 'comando no encontrado' en Windows, lo que significa que python no está en su ruta estándar.

Comprueba cómo añadir python a tu ruta aquí: [Configurar ruta de instalación en Python](http://superuser.com/questions/143119/how-to-add-python-to-the-windows-path).

## Arranque
Puede utilizar la interfaz de usuario GUI creada con la ayuda de la libreria Tkinter: ```GUI.py```.

## Uso
Luego de abrir ```GUI.py```, ejecute el archivo en la terminal y se abrirá la interfaz de usuario. Cuando la interfaz esté abierta podrá ingresar sus cadenas de prueba y verificar si son aceptadas o rechazadas.

## Limitaciones
- El programa solo funciona con una única expresión regular:

```((x)|(x)+)|((Cv|CV)|(Vc|VC))|((Cv|CV)(cv|Cv|cV|CV)+)|((Vc|VC)(vc|Vc|vC|VC)+)```
## Reglas para diseño de la ER
-	Cadenas numéricas de una o más cifras.
-	Cadenas de texto de longitud par.
-	Cadenas de texto que inicien solo en mayúsculas.
-	Cadenas de texto que no acepten consonantes y/o vocales seguidas.
-	No debe aceptar cadenas combinadas entre texto y números.

