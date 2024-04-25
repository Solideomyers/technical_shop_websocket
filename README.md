# Aplicacion Websocket

![Vite](https://img.shields.io/badge/Vite-B73BFE?style=for-the-badge&logo=vite&logoColor=FFD62E)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)

## Esta es una pequeña aplicacion para probar el uso de websocket.

### La aplicacion se encuentra trabajando en conjunto con la aplicacion de nest, la cual esta desplegada en:

```
https://technicalshop-production.up.railway.app/
```

## Ejecutar en desarrollo

1. Clona el repositorio.
2. Navega hasta la carpeta del proyecto.
3. Instala las dependencias con `npm install`.
4. Ejecuta el proyecto con `npm run dev`.

## Funcionalidad

Lo que se busca con esta aplicacion es detectar las instancias conectadas mediante un token.

1. Para generar un token:

   - Usando `Postman`:
     - metodo: `POST`
     - credenciales:
     ```
     {
         "email": "test1@example-pet-store",
         "password": "Abc1234"
     }
     ```
     - endpoint:
     ```
     https://technicalshop-production.up.railway.app/api/auth/login
     ```

2. Pega el token generado en la casilla correspondiente. Y puedes seguir el mismo procedimiento para crear otra instancia y enviar mensajes entre los usuarios conectados.

---

<table>
  <tr>
    <td style="vertical-align: middle;"><a href="https://github.com/Solideomyers"><img alt="GitHub" src="https://img.shields.io/badge/-GitHub-181717?style=flat-square&logo=github" /></a></td>
    <td style="vertical-align: middle;"><a href="https://github.com/Solideomyers">Francisco A. Myers M.</a></td>
  </tr>
</table>

[![Deployed with Vercel](https://img.shields.io/badge/Deployed%20with-Vercel-black?style=for-the-badge&logo=vercel)](https://technical-shop-websocket-7m5c3a5d6-solideomyers-projects.vercel.app/)
