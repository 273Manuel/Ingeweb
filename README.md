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
# Tema del proyecto

**Estructura básica de un proyecto web profesional y separación cliente-servidor**

Este proyecto tiene como objetivo aplicar las buenas prácticas de organización de un proyecto web, utilizando **HTML5**, **CSS** y **JavaScript**, así como comprender la importancia de la separación entre cliente y servidor en el desarrollo web moderno.

---

## Propósito y ventajas de la estructura usada

La estructura propuesta sigue un modelo profesional, separando de forma clara los recursos del proyecto:

- **/css** → Contiene las hojas de estilo, lo que facilita mantener y modificar la apariencia sin afectar la estructura HTML.
- **/js** → Archivos JavaScript para la funcionalidad y comportamiento de la página.
- **/assets** → Recursos como imágenes y tipografías, organizados para un acceso rápido.
- **/docs** → Documentación y diagramas que describen la arquitectura del proyecto.
- **index.html** → Archivo principal que sirve como punto de entrada.

**Ventajas:**
1. Facilita el trabajo colaborativo, ya que cada área (estructura, estilo, funcionalidad) está claramente delimitada.
2. Mejora el mantenimiento y escalabilidad del proyecto.
3. Permite que otros desarrolladores comprendan rápidamente dónde encontrar y modificar cada parte del sistema.

---

## Importancia de la separación cliente-servidor

En una arquitectura web moderna, el **cliente** (navegador) se encarga de mostrar la interfaz y manejar la interacción del usuario, mientras que el **servidor** procesa solicitudes, gestiona datos y devuelve respuestas.

**Beneficios de esta separación:**
- **Seguridad:** el código y los datos sensibles permanecen en el servidor.
- **Eficiencia:** el servidor procesa y entrega solo lo necesario, optimizando la carga.
- **Escalabilidad:** se pueden modificar la interfaz o la lógica del servidor sin afectar la otra parte.
- **Flexibilidad tecnológica:** el c


¡Perfecto! 🙌 Te dejo la documentación lista para que solo copies y pegues en tu parcial, siguiendo el mismo estilo que usaste antes:

---

# Tema del Proyecto

Visualizador Interactivo de Datos CSV con Accesibilidad y Gráficos Dinámicos

Este proyecto tiene como objetivo construir una aplicación web de una sola página (SPA) que permita al usuario pegar o importar datos en formato CSV y visualizarlos tanto en una tabla interactiva como en gráficos configurables. Además, el proyecto integra principios de **accesibilidad** basados en la WCAG para garantizar que sea usable por personas con diferentes tipos de discapacidad.

---

## Propósito y ventajas de la aplicación

La aplicación está diseñada para simular una herramienta básica de inteligencia de negocios (BI), similar a funciones esenciales de Excel, pero directamente en el navegador.

**Ventajas principales:**

* Permite cargar datos CSV desde texto plano o archivos.
* Muestra automáticamente los datos en una tabla estructurada.
* Genera gráficos dinámicos (barras verticales u horizontales, entre otros).
* Ofrece personalización: elección de columnas para eje X e Y, modo oscuro y filtros por columna.
* Incluye opción de exportar los gráficos como imágenes PNG para usarlos en informes o presentaciones.

Esto convierte a la aplicación en una herramienta ligera, práctica y adaptable para el análisis rápido de información.

---

## Estructura básica del proyecto

├── index.html                
├── /css/
│   └── estilos.css         
├── /js/
│   └── script.js              
├── /assets/
│   └── logo.png               
└── /docs/
    └── diagrama-estructura.png 



**Ventajas de esta estructura:**

* Facilita el mantenimiento, al separar claramente la lógica (JS), estilo (CSS) y estructura (HTML).
* Permite escalar la aplicación para incluir más tipos de gráficos o funciones sin romper la organización.
* Hace que cualquier desarrollador pueda ubicar rápidamente dónde modificar cada parte del sistema.

---

## Importancia de la accesibilidad (WCAG)

La aplicación cumple con criterios de accesibilidad según las **Pautas de Accesibilidad al Contenido Web (WCAG)**, incluyendo:

* **Perceptible:** contraste adecuado entre colores (blanco y negro) y soporte de modo oscuro.
* **Operable:** navegación por teclado para acceder a todas las opciones (formularios, selectores, botones).
* **Comprensible:** mensajes de error claros cuando el CSV está mal formateado.
* **Robusto:** compatible con tecnologías de asistencia como lectores de pantalla.

Se consideraron al menos 3 tipos de discapacidad:

* **Visual:** contraste alto, tipografías legibles, soporte de lectores de pantalla.
* **Motora:** controles accesibles mediante teclado, sin depender únicamente del mouse.
* **Cognitiva:** interfaz clara, con instrucciones simples y mensajes de advertencia.

---

## Importancia de la separación cliente-servidor

Aunque esta aplicación se ejecuta totalmente en el cliente, el modelo conceptual sigue la filosofía de separar responsabilidades:

* **Cliente (frontend):** encargado de la interfaz, lectura del CSV, renderizado de tablas y gráficos.
* **Servidor (backend, opcional en versiones futuras):** encargado de almacenar grandes volúmenes de datos, procesarlos y devolver resultados preprocesados.

**Beneficios de esta separación:**

* **Seguridad:** datos sensibles o masivos pueden mantenerse en el servidor.
* **Eficiencia:** el servidor puede procesar y enviar solo los resultados necesarios.
* **Escalabilidad:** permite extender la aplicación hacia un modelo cliente-servidor completo en caso de integrarla con bases de datos o APIs.
* **Flexibilidad:** facilita reemplazar tecnologías en el cliente o servidor sin afectar la otra parte.


Para que el proyecto funcione tienes que poner en el terminal:
!. npm install
2. npm run dev
Y listo :3

---


