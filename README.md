Estructura del proyecto
/IngeWebA3/ ├── index.html ├── ingenieriaweb.html ├── clienteservidor.html ├── html5.html ├── /css/ │ └── estilos.css ├── /js/ │ └── script.js └── /docs/ └── diagrama-estructura.png

Explicación:

index.html: Página principal con la historia de la ingeniería web.
Los demás archivos .htmlcontienen explicaciones específicas según el tema.
Las carpetas /css/y permiten separar estilos, /js/scripts /docs/y documentación gráfica.
El archivo README.mddocumenta todo el proyecto, su estructura y cómo ejecutarlo.
Cómo clonar y visualizar el proyecto desde GitHub
¿Qué significa clonar un repositorio?
Clonar un repositorio es el proceso de copiar todo el contenido de un proyecto desde GitHub a tu computadora local. Esto te permite:

Ver, modificar y ejecutar los archivos del proyecto.
Trabajar localmente sin conexión permanente a internet
Enviar cambios al repositorio remoto (si tienes permisos)
Requisitos previos
Tener Git instalado:

Verificar congit --version
Si no lo tienes, descárgalo desde https://git-scm.com
Acceda a internet y navegador para obtener la URL del repositorio

Un editor de código recomendado: Visual Studio Code ( https://code.visualstudio.com )

Cómo clonar el repositorio en Linux
Abre la terminal (Ctrl + Alt + T o buscar en el menú de aplicaciones)

Verifica si Git está instalado:

git --versión

Si no lo esta, instala con: sudo apt update sudo apt install git

Elige una carpeta para clonar el proyecto: cd Documentos Si no sabes cómo ver las carpetas desde el terminal utiliza el comando ls el cual visualiza las carpetas

Copia la URL del repositorio desde GitHub:https://github.com/273Manuel/Ingeweb.git

Ingrese a https://github.com/273Manuel/Ingeweb.git
Haz clic en el botón "Code" y copia el enlace HTTPS
Clona el repositorio: git clone 

Acceda a la carpeta del proyecto: cd Ingeweb

Abra el archivo index.html en el navegador: xdg-open index.html

Cómo clonar el repositorio en Windows
Instale Git desde: https://git-scm.com/download/win
Abre el programa Git Bash (viene incluido con Git)
Elige una carpeta de destino, por ejemplo: cd /c/Users/TuUsuario/Documentos
Copia la URL del repositorio desde GitHub:
Ingrese a https://github.com/273Manuel/Ingeweb.git
Haz clic en "Código" y copia el enlace HTTPS
Clona el repositorio: git clone https://github.com/273Manuel/Ingeweb.git
Acceder al proyecto: cd IngeWebA3
Abre index.html en tu navegador con doble clic o usa Visual Studio Code: code .
Reflexión en equipo
¿Por qué organizar de forma semántica los contenidos facilita el trabajo colaborativo y el mantenimiento del sitio?
Porque permite que cualquier miembro del equipo comprenda fácilmente la estructura y el propósito de cada parte del documento. Las etiquetas semánticas describen el contenido de manera clara y hacen que el código sea más legible, tanto para personas como para máquinas.

##Tres ventajas observadas del uso de HTML5 moderno:

Mejora la accesibilidad para todos los usuarios, incluidas personas con discapacidad.
Facilita el posicionamiento en buscadores gracias a su estructura clara.
Hace el código más limpio, ordenado y fácil de mantener.
