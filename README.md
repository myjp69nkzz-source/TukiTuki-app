# Tuki Tuki — App de Pedidos 🧸

App de catálogo y pedidos por WhatsApp para la juguetería didáctica **Tuki Tuki** (Manta, Ecuador).

---

## 🚀 Cómo publicarla para tus clientes (paso a paso)

No necesitas instalar nada en tu computadora. Solo una cuenta de GitHub (gratis) y una de Vercel (gratis).

### Paso 1 — Sube el proyecto a GitHub

1. Entra a **https://github.com** e inicia sesión (o crea tu cuenta).
2. Haz clic en el botón verde **"New"** (o ve a https://github.com/new) para crear un repositorio.
3. Ponle un nombre, por ejemplo: `tukituki-app`.
4. Déjalo en **Public** y haz clic en **"Create repository"**.
5. En la página que aparece, busca el enlace que dice **"uploading an existing file"** (subir un archivo existente).
6. **Arrastra TODOS los archivos y la carpeta `src`** de este proyecto a esa ventana.
   - Importante: sube la carpeta `src` completa, más los archivos `index.html`, `package.json`, `vite.config.js`, `.gitignore` y este `README.md`.
7. Abajo, haz clic en **"Commit changes"**.

### Paso 2 — Conéctalo a Vercel y publica

1. Entra a **https://vercel.com** y haz clic en **"Sign Up"**.
2. Elige **"Continue with GitHub"** (así conectas tu cuenta automáticamente).
3. Una vez dentro, haz clic en **"Add New..."** → **"Project"**.
4. Busca tu repositorio `tukituki-app` y haz clic en **"Import"**.
5. Vercel detecta solo que es un proyecto **Vite**. No cambies nada.
6. Haz clic en **"Deploy"**.
7. Espera ~1 minuto. ¡Listo! Vercel te dará un link tipo:
   **https://tukituki-app.vercel.app**

Ese link ya lo puedes compartir con tus clientes por WhatsApp, Instagram, etc. 🎉
La app cargará rápido porque Vercel la compila por ti.

---

## ✏️ Cómo cambiar cosas después (precios, productos)

Toda la información de los productos está en el archivo **`src/App.jsx`**, en la sección `const PRODUCTS = [ ... ]`.
Puedes editar ese archivo directamente en GitHub (lápiz ✏️) y Vercel volverá a publicar los cambios automáticamente en segundos.

El número de WhatsApp donde llegan los pedidos también está en `src/App.jsx`, busca: `wa.me/593983500844`.

---

## 🌐 Conectar tu dominio propio (opcional)

Si más adelante quieres usar `tukituki.ec` en vez del link de Vercel:
1. Compra el dominio (en un registrador como GoDaddy, Namecheap, etc.).
2. En Vercel, entra a tu proyecto → **Settings** → **Domains** → agrega tu dominio y sigue las instrucciones.

---

## 💻 (Solo si sabes programar) Correr localmente

```bash
npm install
npm run dev
```
