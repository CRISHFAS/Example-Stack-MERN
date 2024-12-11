# mern-stack-example

Antes de comenzar...
- Asegúrese de estar familiarizado con Node.js y React.js. 
- También necesitará acceso a una base de datos de MongoDB Atlas.

## Configuración del proyecto 

[Clone el Repositorio de GitHub](https://github.com/CRISHFAS/Example-Stack-MERN)

### Cómo correr?

Cree el archivo con el URI de Atlas y el puerto del servidor en:`mern/server/config.env`

```
ATLAS_URI=mongodb+srv://<username>:<password>@sandbox.jadwj.mongodb.net/
PORT=5050
```

Servidor de inicio:
```
cd mern/server
npm install
npm start
```

Iniciar servidor web:
```
cd mern/client
npm install
npm run dev
```