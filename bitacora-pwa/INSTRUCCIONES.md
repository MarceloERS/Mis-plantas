# 🌿 Bitácora de Plantas — Chillán
## Cómo instalar en tu iPhone como app

---

### Paso 1: Subir los archivos a internet

Necesitás subir **toda esta carpeta** a un hosting gratuito. La opción más fácil es:

#### Opción A — Netlify Drop (recomendada, sin cuenta)
1. Ve a **https://app.netlify.com/drop**
2. Arrastrá toda la carpeta `bitacora-pwa` al recuadro
3. Netlify te dará un link como `https://random-name.netlify.app`
4. ¡Listo! Ese es tu link personal.

#### Opción B — GitHub Pages (requiere cuenta de GitHub)
1. Crea un repositorio en github.com
2. Sube todos los archivos
3. Ve a Settings → Pages → Deploy from branch `main`
4. Tu app estará en `https://tuusuario.github.io/nombre-repo`

---

### Paso 2: Agregar a la pantalla de inicio del iPhone

1. Abrí **Safari** en tu iPhone (debe ser Safari, no Chrome)
2. Entrá al link de tu app
3. Tocá el botón de **compartir** (el cuadrado con flecha hacia arriba ↑)
4. Buscá y tocá **"Agregar a pantalla de inicio"**
5. Dale el nombre que quieras → **Agregar**

¡Ya tenés tu app con ícono en la pantalla de inicio! 🎉
Se abre en pantalla completa, sin barra de Safari, como una app nativa.

---

### Funciona sin internet
Una vez que la hayas abierto al menos una vez con conexión, la app guarda todo localmente y **funciona offline**.

---

### Archivos incluidos
```
bitacora-pwa/
├── index.html          ← La app principal
├── manifest.json       ← Configuración PWA
├── sw.js               ← Service Worker (offline)
├── icons/
│   ├── icon-192.png
│   ├── icon-512.png
│   ├── apple-touch-icon.png
│   ├── apple-touch-icon-152.png
│   └── apple-touch-icon-167.png
└── INSTRUCCIONES.md    ← Este archivo
```
