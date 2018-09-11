# Instalación y Configuración de Jupyter Notebook

------------------------------------------------
Instalación de Jupyter Notebook en Windows  
Instituto Tecnológico de Costa Rica 	      
Escuela de Ingeniería en Computación       
Curso: Inteligencia Artificial	      
Semestre 2 - 2018		 	      
Proyecto corto 2 			      
Estudiantes: 			      
* Jonathan Martínez Camacho 	      
* Mariana Rojas Semeraro 		      
* Diego Tenorio Solís 		      
------------------------------------------------

---------------	
Requerimientos:
---------------

* De preferencia tener instalado la última versión de Python, la cual se encuentra disponible en: https://www.python.org/downloads/

--------------------------------
Instalación del Jupyter Notebook
--------------------------------

En este caso se utilizara el asistente de instalación de Python llamado pip, por lo cual basta con abrir un cmd (Tecla de windows + R) y dirigirse hacia la carpeta donde este se encuenta instalado. Una vez ahi se ejecuta los siguientes comandos:

* python -m pip install --upgrade pip
* python -m pip install jupyter

* Nota: en caso de que Python ya se encuentre como una variable de entorno en el sistema bastara solamente abrir el cmd y ejecutar los anteriores comandos.


-----------------------------------------------------
Instalación y configuración de bibliotecas necesarias
-----------------------------------------------------

* Nota: al igual que con la instalación de Jupyter Notebook se necesita hacer uso del asistente de instalación pip, por lo cual se requiere que acceder a la carpeta donde este está instalado o en caso de que se encuentre como una variable de entorno nada más ejecutar los comandos sin moverse entre directorios.

----------------------------------------
Instalación de Graphviz en Windows
----------------------------------------

* pip install graphviz
* Ir a https://graphviz.gitlab.io/_pages/Download/Download_windows.html y descargar graphviz-2.38.msi, e instalarlo como cualquier programa. No modificar el directorio de instalación que se da por defecto.

----------------------------------------
Instalación de Graphiz en Linux (Ubuntu)
----------------------------------------

* pip install graphviz
* sudo apt-get install graphviz

----------------------------------------
Instalación de Graphiz en Mac
----------------------------------------

* /usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)" este link instalara un asistente de instalación llamada Homebrew. Después de la instalación de Homebrew, ejecutar:
* brew install graphviz
* pip install python-graphviz

----------------------------------------
Instalación de Numpy
----------------------------------------
* pip install numpy

----------------------------------------
Instalción de Scipy
----------------------------------------
* pip install scipy

----------------------------------------
Instalación de Pandas
----------------------------------------
* pip install pandas

----------------------------------------
Instalación de Scikit-learn
----------------------------------------
* pip install -U scikit-learn

De esta forma Jupyter y sus librerías están listas para ser utilizadas.

-------------
GitHub
-------------

* https://github.com/jonathan1712/Tree-Decision.git
