Para que tu documento en GitHub se vea **exactamente igual que en las imágenes** (bien estructurado, con sangrías, líneas, íconos de árbol, títulos grandes y resaltados), debes **usar correctamente Markdown (`README.md`)**.

Aquí tienes el contenido que puedes **copiar y pegar directamente en tu archivo `README.md`** para que se vea como en tus capturas:

---

```markdown
# Estructura del proyecto

```

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

````

### Explicación:

- `index.html`: Página principal con la historia de la ingeniería web.
- Los demás archivos `.html` contienen explicaciones específicas según el tema.
- Las carpetas `/css/`, `/js/` y `/docs/` permiten separar estilos, scripts y documentación gráfica.
- El archivo `README.md` documenta todo el proyecto, su estructura y cómo ejecutarlo.

---

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

   ```bash
   git --version
````

Si no lo está, instala con:

```bash
sudo apt update
sudo apt install git
```

3. Elige una carpeta para clonar el proyecto:

   ```bash
   cd Documentos
   ```

   Si no sabes cómo ver las carpetas desde el terminal, usa `ls` para listarlas.

4. Copia la URL del repositorio desde GitHub:

   * Ingrese a: [https://github.com/273Manuel/Ingeweb.git](https://github.com/273Manuel/Ingeweb.git)
   * Haz clic en el botón **"Code"** y copia el enlace **HTTPS**

5. Clona el repositorio:

   ```bash
   git clone https://github.com/273Manuel/Ingeweb.git
   ```

6. Accede a la carpeta del proyecto:

   ```bash
   cd Ingeweb
   ```

7. Abre el archivo `index.html` en el navegador:

   ```bash
   xdg-open index.html
   ```

---

## Cómo clonar el repositorio en **Windows**

1. Instala Git desde: [https://git-scm.com/download/win](https://git-scm.com/download/win)

2. Abre el programa **Git Bash** (viene con Git).

3. Elige una carpeta de destino, por ejemplo:

   ```bash
   cd /c/Users/TuUsuario/Documentos
   ```

4. Copia la URL del repositorio desde GitHub:

   * Ingrese a: [https://github.com/273Manuel/Ingeweb.git](https://github.com/273Manuel/Ingeweb.git)
   * Haz clic en "Código" y copia el enlace HTTPS

5. Clona el repositorio:

   ```bash
   git clone https://github.com/273Manuel/Ingeweb.git
   ```

6. Accede al proyecto:

   ```bash
   cd Ingeweb
   ```

7. Abre `index.html` con doble clic o usa Visual Studio Code:

   ```bash
   code .
   ```

---

# Reflexión en equipo

## ¿Por qué organizar de forma semántica los contenidos facilita el trabajo colaborativo y el mantenimiento del sitio?

Porque permite que cualquier miembro del equipo comprenda fácilmente la estructura y el propósito de cada parte del documento. Las etiquetas semánticas describen el contenido de manera clara y hacen que el código sea más legible, tanto para personas como para máquinas.

### Tres ventajas observadas del uso de HTML5 moderno:

1. Mejora la accesibilidad para todos los usuarios, incluidas personas con discapacidad.
2. Facilita el posicionamiento en buscadores gracias a su estructura clara.
3. Hace el código más limpio, ordenado y fácil de mantener.

```

---

✅ **Pega todo eso tal como está en tu archivo `README.md` en GitHub y se verá igual que en tus imágenes.**

Si quieres, también te puedo generar directamente el archivo `.md` o PDF para subirlo. ¿Te gustaría eso?
```
