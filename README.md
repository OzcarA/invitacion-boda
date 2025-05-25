# Invitación de Boda Interactiva 💍

¡Bienvenido/a! Este proyecto es una invitación de boda interactiva y en tiempo real, perfecta para compartir por WhatsApp o redes sociales.

## ✨ Características

- Diseño elegante y adaptado a móviles con Tailwind CSS.
- Formulario para confirmar asistencia (RSVP).
- Lista de confirmados visible en tiempo real (con Firebase).

## 🚀 Cómo publicarlo en GitHub Pages

1. **Sube el archivo `index.html` a tu repositorio.**
   - Ve a [github.com](https://github.com) y crea un nuevo repositorio público.
   - Sube el archivo desde este zip (`index.html`).

2. **Activa GitHub Pages**
   - Entra en `Settings` > `Pages`.
   - En `Source` selecciona `main` y carpeta `/ (root)`.
   - Guarda y espera unos segundos.
   - Visita la URL que GitHub te dará (ej: `https://tuusuario.github.io/invitacion-boda`).

## 🔧 Cómo configurar Firebase

1. Ve a [Firebase Console](https://console.firebase.google.com) y crea un nuevo proyecto.
2. Activa **Realtime Database** en modo prueba.
3. Crea una nueva App Web (ícono `</>`), copia las claves de configuración.
4. Reemplaza el bloque `firebaseConfig` en `index.html` con tus datos.

```js
const firebaseConfig = {
  apiKey: "TU_API_KEY",
  authDomain: "TU_DOMINIO.firebaseapp.com",
  databaseURL: "https://TU_DOMINIO.firebaseio.com",
  projectId: "TU_ID",
  storageBucket: "TU_BUCKET",
  messagingSenderId: "TU_SENDER_ID",
  appId: "TU_APP_ID"
};
```

5. ¡Listo! Los invitados que confirmen se guardarán y verán en tiempo real.

---

**¡Felicidades por tu boda! 🎉**  
Diseñado con amor para un día inolvidable.
