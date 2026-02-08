# Práctica UT6 – Despliegue de un sitio estático en GitHub Pages

## Descripción general

Esta práctica consiste en la creación, versionado y publicación de un sitio web estático utilizando **Git** como sistema de control de versiones y **GitHub Pages** como servicio de alojamiento.  
El objetivo es comprender el flujo completo de trabajo: desde el desarrollo local hasta el despliegue automático en Internet, relacionándolo con el Resultado de Aprendizaje 6 (RA6).

La práctica se ha realizado siguiendo una metodología incremental, documentando cada fase mediante commits atómicos y mensajes descriptivos.

---

## Entorno de trabajo

- **Sistema operativo:** Linux Mint  
- **Editor de código:** Visual Studio Code  
- **Control de versiones:** Git  
- **Repositorio remoto:** GitHub  
- **Despliegue:** GitHub Pages  

El uso de Linux facilita el trabajo con Git y SSH al ser herramientas nativas del sistema.

---

## 1. Creación de la plantilla inicial

Se ha creado una estructura básica de sitio web estático compuesta por los siguientes archivos:

- `index.html` – Página principal del sitio.
- `style.css` – Hoja de estilos con el diseño base.
- `script.js` – Script JavaScript con un mensaje de consola.

Una vez creados los archivos con el contenido base proporcionado, se inicializó un repositorio Git local y se realizó el **primer commit**, que marca el estado inicial del proyecto.

**Commit realizado:**
- *Etapa 1: plantilla inicial del sitio*

---

## 2. Personalización del sitio

A partir de la plantilla base se realizaron varias personalizaciones mínimas:

- Cambio del **título de la página** y de los textos principales en `index.html`.
- Modificación del **color de la cabecera y del pie de página** en `style.css`.
- Personalización del **mensaje mostrado en la consola** en `script.js`.

Cada conjunto de cambios se agrupó en commits independientes para mantener un historial claro y ordenado.

---

## 3. Configuración de GitHub y conexión del repositorio

Se creó un repositorio remoto en GitHub y se enlazó con el repositorio local utilizando **conexión SSH**.

**Motivo de la elección de SSH:**
- Permite una autenticación segura mediante claves criptográficas.
- Evita introducir usuario y contraseña o tokens en cada `push`.
- Es el método recomendado para un uso continuado de GitHub.

---

## 4. Commits atómicos realizados

Durante la práctica se realizaron varios commits significativos y coherentes, entre ellos:

- *Etapa 3: personalización de títulos y textos*
- *Etapa 4: cambio de paleta de colores*
- *Etapa 5: personalización del script*

Cada commit representa una mejora concreta del proyecto, facilitando el seguimiento de la evolución del sitio.

---

## 5. Publicación con GitHub Pages

Se activó **GitHub Pages** desde la configuración del repositorio, utilizando la rama `main` como origen y la carpeta raíz (`/`).

🔗 **URL pública del sitio web:**  
👉 https://https://xcriss16.github.io/mi_blog//

Tras cada `git push`, GitHub Pages actualiza automáticamente el sitio, lo que ejemplifica un proceso básico de **integración continua**.

---

## 6. Dominio personalizado (opcional)

No se ha configurado un dominio personalizado para esta práctica.  
Este paso se considera opcional y no afecta a la evaluación básica del ejercicio.

---

## 7. Reflexión final

A lo largo de la práctica he aprendido a:

- Utilizar Git como herramienta de control de versiones para registrar cambios de forma ordenada.
- Trabajar con repositorios remotos en GitHub y entender la diferencia entre HTTPS y SSH.
- Desplegar un sitio web estático de forma automática mediante GitHub Pages.
- Valorar la importancia de la documentación y de los commits atómicos en proyectos de desarrollo web.

Esta práctica demuestra cómo un repositorio bien organizado puede actuar como fuente de documentación y despliegue al mismo tiempo.

---

## Autor

Cristian
