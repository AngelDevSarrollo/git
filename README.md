# Mi Repositorio de Git 
Bienvenido a mi repositorio de Git. Este repositorio contiene ejemplos y comandos básicos para trabajar con Git. Es una guía útil para principiantes que quieren aprender a utilizar Git y GitHub.

Contenido
Instalación de Git
Configuración Inicial
Comandos Básicos de Git
Clonar un Repositorio
Inicializar un Repositorio
Agregar Cambios
Confirmar Cambios
Ver el Estado
Ver el Historial
Crear y Cambiar Ramas
Fusionar Ramas
Subir Cambios al Repositorio Remoto
Actualizar el Repositorio Local
Instalación de Git
Para instalar Git, sigue las instrucciones en la página oficial de Git.

Configuración Inicial
Configura tu nombre de usuario y correo electrónico:

bash
Copy code
git config --global user.name "Tu Nombre"
git config --global user.email "tuemail@example.com"
Comandos Básicos de Git
Clonar un Repositorio
Clona un repositorio existente desde GitHub a tu máquina local:

bash
Copy code
git clone https://github.com/usuario/repositorio.git
Inicializar un Repositorio
Inicializa un nuevo repositorio en tu máquina local:

bash
Copy code
git init
Agregar Cambios
Agrega archivos al área de preparación (staging area):

bash
Copy code
git add nombre_del_archivo
Para agregar todos los archivos:

bash
Copy code
git add .
Confirmar Cambios
Confirma los cambios en el repositorio local con un mensaje descriptivo:

bash
Copy code
git commit -m "Mensaje de confirmación"
Ver el Estado
Muestra el estado de los archivos en el repositorio:

bash
Copy code
git status
Ver el Historial
Muestra el historial de confirmaciones:

bash
Copy code
git log
Crear y Cambiar Ramas
Crea una nueva rama:

bash
Copy code
git branch nombre_de_la_rama
Cambia a una rama existente:

bash
Copy code
git checkout nombre_de_la_rama
O crea y cambia a una nueva rama:

bash
Copy code
git checkout -b nombre_de_la_rama
Fusionar Ramas
Fusiona una rama con la rama actual:

bash
Copy code
git merge nombre_de_la_rama
Subir Cambios al Repositorio Remoto
Sube los cambios al repositorio remoto:

bash
Copy code
git push origin nombre_de_la_rama
Actualizar el Repositorio Local
Actualiza tu repositorio local con los cambios del repositorio remoto:

bash
Copy code
git pull
