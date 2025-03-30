# Bitcoin Guide Node Nation

Esta guía práctica y divertida que te llevará a través de los conceptos clave de Bitcoin en la que aprenderás conocimientos sobre econommía y tecnología, desde su origen hasta temas más avanzados como minería y lightning network. Los notebooks de Jupyter incluidos cubren los siguientes bloques de información y actividades:

- Bloque 0: Dinero Sólido (Educación financiera) 
- Bloque 1: Introducción a Bitcoin / (Minisfiesto cypherpunk, Libro blanco de Bitcoin y tecnología que inspiró la creación de Bitcoin)
- Bloque 2: La tecnología Bitcoin (Estructura de transacciones, datos de Bloques y firmas digitales)
- Bloque 3: Minería de Bitcoin 1 (Programación y ejecución de mineros Bitcoin)
- Bloque 4: Minería de Bitcoin 2 (Instalación de un Nodo de Bitcoin)
- Bloque 5: Lightning Network (Ejecuta un Nodo de Lightning Network y haz pagos con una interfaz de usuario por medio de una API)
- Bloque 6: Caída a la madriguera del conejo (Taller de GPG, Podcast, maneras de ganar sats)

## Instalación de Jupyter Notebook

![alt text](https://github.com/PupusasGame/Node-Nation-Student-Guide/blob/main/images/jupyter_pyhton.png)

### Windows

1. **Descarga Python**
   - Ve a la página de descarga de Python: https://www.python.org/downloads/(https://www.python.org/downloads/)
   - Ejecuta el instalador:
   	- clic derecho ejecutar como administrador

2. **Instala Python como administrador:**
   - Ejecuta el instalador y sigue las instrucciones, normalmente sólo necesitas dar clic en siguiente o aceptar según sea el caso.

3. **Modifica python como administrador:**
   - Ejecuta el instalador una vez más con un clic derecho ejecutar como administrador
   - Haz clic en la opción modificar en la nueva instalación
   - Activa todas las casillas de la nueva instalación y haz clic en siguiente o aceptar según sea el caso
   
4. **Ejecutar Powershell como administrador:**
   - Haz clic en el botón windows, busca powershell en la casilla de buscador
   - Ejecuta powershell como administrador haciendo clic derecho, luego elige la opción ejecutar como administrador
   
5. **Revisar si la instalación de python3 se ejecutó de la manera correcta:**
   - escribe estos comandos en la terminal y ejecutalos presionando Enter:
   	1. python 
   	(si la instalación fue exitosa, una nueva línea con este símbolo: >>> escribe exit() para salir, si la instalación no fue exitosa tendrás un error y probablemente necesitas reiniciar tu equipo)
   	2. python -m pip install --upgrade pip
   	(actualiza pip)
   	3. pip
   	(verás una lista de comandos al ejecutar este comando)
   	3. pip install jupyter notebook 
   	(o puedes intentar con este otro: python -m pip install jupyter) 
   	
6. **Ejecutar Jupyer Notebook**
   - escribe esto en la terminal:
   	1. jupyter notebook
   - esto ejecutará un servidor propio de Jupyer Notebook:
   	1. busca la línea que dice: Jupyter Server 2.14.2 is running at:
   	(Significa que jupyter ya está corriendo, y que en la siguiente línea podrás ver tu enlace para acceder al notebook) algo como esto: http://127.0.0.1:8888/tree?token=fd12f34a0e208e3a36a8259a7d59fe7cf2d683f4d42c104f copia y pega en tu navegador web lo que muestra tu terminal powershell.

### macOS

1. **Descarga Anaconda:**
   - Ve a la página de descarga de Anaconda: https://www.anaconda.com/download (https://www.anaconda.com/download)
   - Descarga la versión de Python 3 para macOS.

2. **Instala Anaconda:**
   - Abre el archivo descargado y sigue las instrucciones.

3. **Inicia Jupyter Notebook:**
   - Abre una terminal y escribe `jupyter notebook`.

### Linux Ubuntu 20.04 y 22.04

1. **Actualiza los paquetes:**
sudo apt update
sudo apt upgrade

2. **Instala Python 3 y pip**

sudo apt install python3 python3-pip

3. **Instala Jupyter Notebook**

pip3 install jupyter

4. **Inicia Jupyer Notebook**

jupyter notebook

**Recuerda cambiar el tema de jupyter: settings/theme/jupyertlab dark para disfrutar de una mejor experiencia**
#### Kids deserve fun while learning Bitcoin, I'm making learning fun again!

X account: @PupusasG
X account: @NodeNationSV
nodenation@getalby.com
pupusasg@zeuspay.com
