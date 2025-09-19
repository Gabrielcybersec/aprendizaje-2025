# Local WordPress (LocalWP) — Instrucciones rápidas para GitHub

Guía mínima para descargar, crear y acceder a un sitio WordPress local usando **Local (LocalWP)**. Copia y pega este `README.md` en tu repositorio.

---

## Requisitos
- Sistema operativo: Windows / macOS / Linux (elige el instalador en https://localwp.com)
- 2 GB+ de RAM recomendada para la VM/entorno local
- Espacio en disco: 2 GB mínimo

---

## Pasos — Instalación y creación del sitio

1. **Descargar e instalar Local**
   - Ir a: `https://localwp.com`
   - Descargar el instalador correspondiente a tu sistema operativo y seguir el asistente de instalación.

2. **Abrir Local**
   - Ejecuta la aplicación **Local** (LocalWP) tras la instalación.

3. **Crear nuevo sitio**
   - Haz clic en **Create a new site**.
   - **Site Name:** `mi-portfolio-wp`
   - **Environment:** selecciona **Preferred** (o **Custom** si conoces la versión de PHP/MySQL que necesitas).
   - Completa el formulario de **Admin**:
     - **Admin Username:** elige el que prefieras (ej.: `admin`)
     - **Admin Password:** elige una contraseña segura (apúntala)
     - **Admin Email:** tu correo (apúntalo)

4. **Local levanta el sitio automáticamente**
   - Local creará la configuración y levantará el servidor local.
   - Haz clic en **Open Site** para abrir la URL generada.
   - URL típica (local): `http://mi-portfolio-wp.local` (puede variar ligeramente según tu instalación).

5. **Acceder al panel de WordPress (WP Admin)**
   - Entra a: `http://mi-portfolio-wp.local/wp-admin`
   - Inicia sesión con el **Admin Username** y **Admin Password** que configuraste.
