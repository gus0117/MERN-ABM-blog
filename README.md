# Proyecto Fullstack MERN ABM blog

Te doy la bienvenida a este proyecto fullstack! Para el backend se utilizó **NodeJS**, **MongoDB** y **Express**. Para el desarrollo del frontend se utilizó **React**.

## Herramientas utilizadas

- VSCode
- NodeJS
- MongoDB
- Express
- Bootstrap 5

## Instrucciones

Para descargar el proyecto se recomienda el uso de GIT con el siguiente comando.

```bash
$git clone https://github.com/gus0117/MERN-ABM-blog.git
```
En este proyecto se encuentran dos carpetas

```
fullstack_node_react
|
|+--- node
|+--- reactfront
```

Para ambas carpetas es necesario abrir una consola dentro de cada carpeta e instalar las dependencias con el comando:

```bash
$npm install
```

El archivo **Base de datos - blogs.txt** contiene unos datos iniciales para cargar manualmente en **MongoDB**. Esto es opcional, ya que el proyecto se ejecutara sin los datos.

En la base de datos debe existir un documento llamado **mean**, pero puedes configurar esto en el archivo:

db.js
```js
const url = 'mongodb://localhost:27017/mern'
```

La carpeta **node** es el proyecto backend, desarrollado con **NodeJS**, **Express** y **MongoDB**. Para desplegarlo de forma local es necesario abrir una consola dentro de esta carpeta y ejecutar el comando

```bash
$node App.js
```

La carpeta **reactfront** es el propio frontend, para ejecutarlo se debe abrir una terminal y escribir el siguiente comando:

```bash
$npm start
```

## Referencias

- https://expressjs.com/es/
- Este proyecto se realizó bajo la guía del canal https://www.youtube.com/c/InformáticaDP/videos