#IngWebA3

## Repositorio de github para el trabajo individual de la asignatura Ingenieria web 1. 

# Cómo clonar y visualizar el proyecto desde GitHub

## ¿Qué significa clonar un repositorio?

Clonar un repositorio es el proceso de copiar todo el contenido de un proyecto desde GitHub a tu computadora local. Esto te permite:

- Ver, modificar y ejecutar los archivos del proyecto.
- Trabajar localmente sin conexión permanente a internet.
- Enviar cambios al repositorio remoto (si tienes permisos).

## Requisitos previos

1. Tener Git instalado:
   - Verificar con `git --version`
   - Si no lo tienes, descárgalo desde [https://git-scm.com](https://git-scm.com)

2. Acceder a internet y navegador para obtener la URL del repositorio.

3. Un editor de código recomendado: Visual Studio Code ([https://code.visualstudio.com](https://code.visualstudio.com))

---

## Cómo clonar el repositorio en **Linux**

1. Abre la terminal (`Ctrl + Alt + T` o buscar en el menú de aplicaciones).
2. Verifica si Git está instalado:

   bash
   git --version


Si no lo está, instala con: sudo apt update sudo apt install git


3. Elige una carpeta para clonar el proyecto: cd Documentos
   
   Si no sabes cómo ver las carpetas desde el terminal, usa `ls` para listarlas.

4. Copia la URL del repositorio desde GitHub:

   * Ingrese a: [https://github.com/273Manuel/Ingeweb.git](https://github.com/273Manuel/Ingeweb.git)
   * Haz clic en el botón **"Code"** y copia el enlace **HTTPS**

5. Clona el repositorio: git clone https://github.com/273Manuel/Ingeweb.git
   
6. Accede a la carpeta del proyecto: cd Ingeweb

7. Abre el archivo `index.html` en el navegador: xdg-open index.html


## Cómo clonar el repositorio en **Windows**

1. Instala Git desde: [https://git-scm.com/download/win](https://git-scm.com/download/win)

2. Abre el programa **Git Bash** (viene con Git).

3. Elige una carpeta de destino, por ejemplo: cd /c/Users/TuUsuario/Documentos

4. Copia la URL del repositorio desde GitHub:

   * Ingrese a: [https://github.com/273Manuel/Ingeweb.git](https://github.com/273Manuel/Ingeweb.git)
   * Haz clic en "Código" y copia el enlace HTTPS

5. Clona el repositorio: git clone https://github.com/273Manuel/Ingeweb.git

6. Accede al proyecto: cd Ingeweb

7. Abre `index.html` con doble clic o usa Visual Studio Code: code .

## Guia 1 ingenieria web: 
### Tema del proyecto


Construcción de una Web Informativa Semántica

Este repositorio contiene una página principal informativa sobre los Fundamentos de la Web Moderna, elaborada con HTML5 siguiendo las buenas prácticas de semántica y accesibilidad. Está dividido en secciones sobre:

Historia de la ingeniería web (en index.html)
¿Qué es la ingeniería web? ( ingenieriaweb.html)
Arquitectura cliente-servidor ( clienteservidor.html)
Semántica y accesibilidad en HTML5 ( html5.html)




### Reflexión individual

---

Al realizar esta actividad, se comprendió que aplicar una estructura semántica en el desarrollo web no solo mejora la organización del código, sino que también permite que sea más claro, accesible y fácilmente entendible por otros programadores. Esta práctica influye positivamente en la usabilidad y en la visibilidad del sitio en motores de búsqueda.

Además, se reconoció la relevancia de incorporar etiquetas como `<header>`, `<main>`, `<section>` y `<footer>`, ya que cumplen funciones esenciales para estructurar lógicamente el contenido de una página. Su uso va más allá del diseño visual, ya que contribuye a mantener un desarrollo coherente y bien ordenado.

Finalmente, se adquirieron habilidades para estructurar adecuadamente los archivos y directorios de un proyecto web, y se aprendió a publicarlos en un repositorio de GitHub utilizando control de versiones, lo cual es clave para mantener un flujo de trabajo colaborativo y profesional.

---

# Estructura del proyecto


/IngeWebA3/
├── index.html
├── ingenieriaweb.html
├── clienteservidor.html
├── html5.html
├── /css/
│   └── estilos.css
├── /js/
│   └── script.js
└── /docs/
└── diagrama-estructura.png


### Explicación:

- `index.html`: Página principal con la historia de la ingeniería web.
- Los demás archivos `.html` contienen explicaciones específicas según el tema.
- Las carpetas `/css/`, `/js/` y `/docs/` permiten separar estilos, scripts y documentación gráfica.
- El archivo `README.md` documenta todo el proyecto, su estructura y cómo ejecutarlo.

---


# Reflexión en equipo

## ¿Por qué organizar de forma semántica los contenidos facilita el trabajo colaborativo y el mantenimiento del sitio?

Porque permite que cualquier miembro del equipo comprenda fácilmente la estructura y el propósito de cada parte del documento. Las etiquetas semánticas describen el contenido de manera clara y hacen que el código sea más legible, tanto para personas como para máquinas.

### Tres ventajas observadas del uso de HTML5 moderno:

1. Mejora la accesibilidad para todos los usuarios, incluidas personas con discapacidad.
2. Facilita el posicionamiento en buscadores gracias a su estructura clara.
3. Hace el código más limpio, ordenado y fácil de mantener.

## Guia 2 ingenieria web: 
### Tema del proyecto
