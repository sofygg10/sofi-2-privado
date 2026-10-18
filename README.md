# Sofi 2.0 · acceso privado

Versión web de Sofi 2.0 protegida con contraseña. La app está cifrada (AES-256-GCM) en `payload.js`; sin la contraseña no se puede leer.

Se genera desde el repo privado `sofi-2` con `npm run publicar -- "CONTRASEÑA"`.

Para olvidar la contraseña guardada en un dispositivo, abre la dirección terminada en `#salir`.
