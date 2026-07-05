# 📲 SubtiVoz PWA — Guía de Instalación en Android

## ¿Qué archivos necesitas?
```
subtivoz-pwa/
├── index.html       ← App principal
├── manifest.json    ← Configuración PWA
├── sw.js            ← Service Worker (offline)
└── icons/
    ├── icon-192.png
    └── icon-512.png
```

---

## Opción 1: Netlify (GRATIS, más fácil) ⭐

1. Ve a **netlify.com** y crea cuenta gratis
2. Arrastra la carpeta `subtivoz-pwa/` completa
3. Netlify te da una URL tipo: `https://subtivoz.netlify.app`
4. En Chrome Android, abre esa URL
5. Chrome mostrará "Agregar a pantalla de inicio" → **Instalar**

---

## Opción 2: GitHub Pages (GRATIS)

1. Crea cuenta en **github.com**
2. Nuevo repositorio público: `subtivoz`
3. Sube los archivos
4. Settings → Pages → Branch: main → Save
5. URL: `https://tu-usuario.github.io/subtivoz`

---

## Opción 3: Vercel (GRATIS)

1. Ve a **vercel.com**
2. "Add New Project" → arrastra la carpeta
3. Deploy → URL lista en segundos

---

## Cómo instalar en Android

Una vez tengas la URL pública:

1. Abre **Chrome** en tu Android
2. Entra a la URL de tu app
3. Toca el menú ⋮ (3 puntos)
4. Toca **"Agregar a pantalla de inicio"**
5. Confirma → ¡La app aparece como ícono!

> **Importante:** Usa Chrome (no Firefox, no Samsung Browser).
> El reconocimiento de voz requiere conexión a internet la primera vez.

---

## Permisos en Android

La primera vez que toques "Iniciar Subtítulos":
- Android pedirá permiso de **micrófono**
- Toca **"Permitir"**
- Si lo rechazaste, ve a: Ajustes → Apps → Chrome → Permisos → Micrófono → Permitir

---

## Idiomas soportados

| Idioma | Código |
|--------|--------|
| Español (España) | es-ES |
| Español (México) | es-MX |
| Español (Argentina) | es-AR |
| Español (Colombia) | es-CO |
| English (US) | en-US |
| Português (Brasil) | pt-BR |
| Français | fr-FR |
| Deutsch | de-DE |

---

## Funciones de la app

- 🎙️ Subtítulos en tiempo real mientras alguien habla
- 📏 Control de tamaño de texto (para mejor visibilidad)
- 🔆 Modo alto contraste (fondo negro, texto amarillo)
- 📋 Copiar toda la transcripción
- ↗️ Compartir por WhatsApp/Telegram/etc.
- 🗑️ Limpiar pantalla
- ⏱️ Contador de tiempo y palabras
- 📵 Pantalla no se apaga mientras escucha
- 📶 Funciona offline (la interfaz, sin reconocimiento de voz)
