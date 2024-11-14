# tpeFundamentos
Para poder ejecutar la Jupyter del trabajo practico especial sin ningun problema hay que seguir los siguientes pasos que comprueban diferentes cuestiones de todo el ambiente:   

- Verificar tener python instalado y que la version descargada en tu computadora sea la version numero 3.12.5 Para poder comprobar esto se puede usar el siguiente comando en la terminal que nos arroja que version es la que estamos usando: "python --version".   
- Clonar el repositorio de Github. Para poder hacer esto hay que situarse en una terminal en la direccion donde queres que se guarde el trabajo practico, ejecutar el comando "git init" y luego el comando "git clone https://github.com/AgustinDimuro/tpeFundamentos.git" el cual descargara el trabajo practico donde estemos parados.   
- Moverse hacia la carpeta del repositorio llamada tpeFundamentos. Para esto hay que usar el comando "cd tpeFundamentos".
- Crear el Virtual Enviroment donde luego instalaremos las librerias necesarias para la correcta compilacion del codigo. Esto se puede hacer con el comando "python -m venv tpeFundamentos" que crea el virtual enviroment con el nombre de tpeFundamentos.   
- Activar el entorno virtual con el comando ".\tpeFundamentos\Scripts\activate". Este paso permite que las instalaciones de las librerias se hagan en este entorno controlado y que no se instalen globalmente.
- Hacer el install del requirements.txt donde alli se encuentran todas las librerias necesarias. El comando que hay que ejecutar es el siguiente: "pip install -r requirements.txt". Asegurarse de que el entorno este activado asi la instalacion se hace alli y no de forma global.   
- En caso de estar en Visual Studio Code seleccionar como kernel aquel que este dentro de la carpeta del enviroment que creamos,siguiendo estos pasos:
    - Abrir Visual Studio Code
    - Hacer click en "Archivo"
    - Seleccionar "Abrir Carpeta"
    - Seleccionamos la carpeta donde esta el proyecto tpeFundamentos
En caso contrario asegurarse que se ejecute la jupyter en el entorno donde instalamos el requirements.txt   

Con todos los pasos anteriormente mencionados ya estamos en condiciones de poder ejecutar todo el codigo incluido en la notebook de Jupyter sin problemas. 