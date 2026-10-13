# Mi Tutora

Plataforma de enseñanza de AIM, desarrollada para DP2 de Ingeniería Informática de la PUCP, ciclo 2022-2.

1. Instala dependencias con `yarn install`.
2. Crea `.env.dev`, requerido por los scripts de inicio y compilación. Revisa `src/config.js` para la URL del backend y las variables de las integraciones que utilices; el servidor de video usa `REACT_APP_VIDEO_SERVER`.
3. Ejecuta `yarn start` (`http://localhost:3000`) o `yarn build` (salida: `build/`).

Validación: `yarn lint`; no hay script de pruebas. Las variables `REACT_APP_*` se incluyen en el navegador: no uses claves secretas de AWS en ellas; la integración de `src/utils/awsConfig.js` requiere sustituirse por un flujo seguro antes de usar credenciales reales.
