# GENIOVA AI · Cuestionario Técnico Ingenieros

Landing web del cuestionario técnico GENIOVA AI con estética _vertical ai_.

Despliegue en **GitHub Pages** con la URL pública por defecto: `https://<usuario>.github.io/geniova-cuestionario/`

## 📁 Contenido

| Archivo | Propósito |
|---|---|
| `index.html` | Landing completa del cuestionario (single page, todo inline) |
| `README.md` | Este archivo |

## 🚀 Despliegue paso a paso (sin terminal, ~3 min)

### 1. Crear el repositorio
- Ve a **https://github.com/new**
- **Repository name:** `geniova-cuestionario`
- **Public** ✅ (necesario para GitHub Pages gratis)
- NO marques "Add README" ni nada más
- Click **Create repository**

### 2. Subir los archivos
- En la página del repo recién creado: **"uploading an existing file"**
- Arrastra `index.html` y `README.md`
- Commit changes

### 3. Activar GitHub Pages
- Pestaña **Settings** (arriba a la derecha del repo)
- Menú lateral: **Pages**
- En *Build and deployment*:
  - **Source:** Deploy from a branch
  - **Branch:** `main` · **Folder:** `/ (root)`
  - **Save**

### 4. Esperar 1-3 minutos
GitHub construye el sitio. Cuando termine, verás un banner verde con la URL:

```
https://<tu-usuario>.github.io/geniova-cuestionario/
```

¡Eso es! Ya está vivo y compartible.

## 📧 Email destino del cuestionario

Las respuestas llegan a:

```
spozo@vertical-ai.es
```

vía **FormSubmit.co** (gratis, sin cuenta).

> ⚠️ La **primera vez** que alguien envíe el formulario, FormSubmit mandará un email de activación a esa dirección. Hay que hacer click en **"Activate Form"** para activarlo. A partir de ahí, todas las respuestas se reciben automáticamente sin más fricción.

### Cambiar el email destino

Edita en `index.html` (línea ~898):

```js
const DESTINATION_EMAIL = 'spozo@vertical-ai.es';
```

Sube el cambio al repo y GitHub Pages se actualiza solo en 1 min.

## ✏️ Personalización rápida

- **Email destino** → línea ~898 de `index.html`
- **Textos del cuestionario** → secciones 01-05 del HTML
- **Colores / estilo** → variables CSS en `:root` (líneas ~12-22)

---

GENIOVA AI · vertical ai · Abril 2026
