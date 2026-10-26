# Savia — demo web

Demo estática con HTML, CSS y JavaScript. No necesita dependencias ni compilación.

## Publicar en Vercel

1. Abre una terminal en esta carpeta.
2. Ejecuta `npx vercel login` para iniciar sesión con tu cuenta.
3. Ejecuta `npx vercel --prod --scope richarandres97-3923s-projects`.
4. Elige crear un proyecto llamado `savia-demo` con framework `Other` y raíz `.`.

La demo conserva reflexiones y progreso en el almacenamiento local del navegador. No incluye cuentas ni sincronización entre dispositivos. El navegador puede ofrecer voces sintéticas distintas según el dispositivo.

## Cambios

El nombre Savia aparece de forma uniforme, incluidos el título, la navegación, los diálogos y los archivos descargables. Se fija la selección de marca para evitar errores con preferencias antiguas.

La publicación mediante la conexión de Vercel quedó pendiente: la API rechazó crear el proyecto con un error 403 de permisos. Este paquete contiene los archivos listos para desplegar.
