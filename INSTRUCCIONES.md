# Sistema Gourmet — Guía para subirlo a internet (gratis, para probar)

Esta guía está pensada para alguien que nunca usó GitHub ni Render.
Vas a tardar unos 15-20 minutos la primera vez.

## Parte 1 — Crear una cuenta en GitHub (donde vive el código)

1. Andá a **https://github.com**
2. Hacé click en "Sign up" (Registrarse) y creá una cuenta gratis con tu email
3. Una vez adentro, hacé click en el botón verde **"New"** (o el símbolo **+** arriba a la derecha → "New repository")
4. Ponele de nombre: `sistema-gourmet`
5. Dejalo en **"Public"** (no hace falta pagar nada)
6. Hacé click en **"Create repository"**

## Parte 2 — Subir los archivos

1. En la página del repositorio recién creado, buscá el link que dice **"uploading an existing file"**
2. Arrastrá ahí estos 3 elementos (manteniendo la carpeta `public` con `index.html` adentro):
   - `server.js`
   - `package.json`
   - la carpeta `public` (con `index.html` adentro)
3. Abajo de todo, hacé click en **"Commit changes"**

## Parte 3 — Crear la cuenta en Render y publicar el sistema

1. Andá a **https://render.com** y registrate gratis (podés usar tu cuenta de GitHub para entrar más rápido)
2. Una vez adentro, hacé click en **"New +"** → **"Web Service"**
3. Conectá tu cuenta de GitHub si te lo pide, y elegí el repositorio `sistema-gourmet`
4. Render va a completar casi todo solo. Revisá que diga:
   - **Build Command:** `npm install`
   - **Start Command:** `npm start`
5. Abajo, elegí el plan **"Free"**
6. Hacé click en **"Create Web Service"**
7. Esperá 2-3 minutos mientras Render prepara todo (vas a ver un texto tipo consola moviéndose — es normal)

## Parte 4 — ¡Lista!

Cuando termine, arriba de la página vas a ver una dirección tipo:

```
https://sistema-gourmet-xxxx.onrender.com
```

Esa es la dirección de tu sistema en internet. Abrila en la notebook, en las tablets, en tu celular — **todos van a compartir los mismos datos automáticamente**, sin instalar nada, solo necesitan internet.

Vas a ver un puntito en la pantalla del sistema:
- 🟢 **En línea** = todo bien, se está guardando y compartiendo
- 🔴 **Sin conexión** = revisá el internet del dispositivo

## Cosas importantes para esta etapa de prueba

- El plan gratis de Render **"se duerme"** después de 15 minutos sin uso. La primera persona que entra después de eso espera unos 30-50 segundos mientras se despierta — es normal, no está roto.
- **Durante esta prueba gratis, los datos pueden llegar a borrarse** si Render reinicia el servicio (pasa alguna vez de forma automática). No es lo ideal para usarlo ya con ventas reales todos los días — es justo para que lo probemos juntos estos días y veamos que todo funcione bien.
- Cuando estemos conformes, pasamos a un plan pago (arranca en unos 7 USD/mes) que no se duerme y le sumamos una base de datos de verdad para que la información nunca se pierda. Ahí también le compramos el dominio lindo (`elgourmet.com.py` o el que seas prefieras).

## Si algo no funciona

Sacale una captura de pantalla a lo que veas (ya sea en GitHub o en Render) y mandámela — la reviso y seguimos.
