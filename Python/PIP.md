# Package Installer for Python

El **Package Installer for Python** (PIP) es el instalador de paquetes (duh) que viene por defecto en python, nos permite instalar módulos para nuestro proyecto.
>Recuerda que si estás dentro de un ambiente virtuaal, los módulos instalados mediante PIP serán solamente pertenecientes a la versión dentro del ambiente virtual y no a la versión general de python instalada en el SO.  

>* **$ pip freeze**
>>Muestra los paquetes instalados.
>* **$ pip install pandas**
>>Instala el módulo indicado (en el caso del ejemplo pandas).
>* **$ pip freeze > requirements.txt**
>>Como tal esto no es más que pasar el standard output a un archivo txt, es una buena práctica utilizada para que un tercero pueda correr el proyecto descargando los módulos indicados en requirements.txt