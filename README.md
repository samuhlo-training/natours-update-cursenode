<div align="center">

<h2>
    <em>Natours</em> - API para gestionar tours y reservas
</h2>
<p>
Proyecto backend desarrollado con Node.js como parte de un curso avanzado. Incluye autenticación, autorización, manejo de datos y API RESTful.
</p>
<p>
Basado en las mejores prácticas de desarrollo backend con Node.js, Express, y MongoDB.
</p>

<p> Creado siguiendo el cursos de <a href="https://codingheroes.io/">Jonas Schmedtmann</a>
</p>

</div>

<div align="center">
    <a href="#empezar">
        Empezar
    </a>
    <span>&nbsp;✦&nbsp;</span>
    <a href="#comandos">
        Comandos
    </a>
    <span>&nbsp;✦&nbsp;</span>
    <a href="#usuario">
        Usuario
    </a>
</div>

<p></p>

<div align="center">

![NodeJS](https://img.shields.io/badge/node.js-6DA55F?style=for-the-badge&logo=node.js&logoColor=white)
![Express.js](https://img.shields.io/badge/express.js-%23404d59.svg?style=for-the-badge&logo=express&logoColor=%2361DAFB)
![MongoDB](https://img.shields.io/badge/MongoDB-%234ea94b.svg?style=for-the-badge&logo=mongodb&logoColor=white)
![Render](https://img.shields.io/badge/Render-%46E3B7.svg?style=for-the-badge&logo=render&logoColor=white)

</div>

<img src="portada.webp"></img>

## Stack

- [**Node.js**](https://nodejs.org/) - Entorno de ejecución para JavaScript en el servidor.
- [**Express**](https://expressjs.com/) - Framework minimalista y flexible para Node.js.
- [**MongoDB**](https://www.mongodb.com/) - Base de datos NoSQL para almacenar los datos de los tours.
- [**Mongoose**](https://mongoosejs.com/) - ODM para MongoDB, simplificando las operaciones con la base de datos.
- [**JWT**](https://jwt.io/) - Autenticación y autorización segura mediante tokens JSON Web.
- [**Parcel**](https://parceljs.org/) - Parcel combina una excelente experiencia de desarrollo lista para usar con una arquitectura escalable que puede llevar su proyecto desde el inicio hasta una aplicación de producción masiva.
- [**PUG**](https://pugjs.org/) - Motor de plantillas para Node.js que permite generar HTML de manera sencilla y eficiente.

## Empezar

### 1. Clona este repositorio:

```bash
git clone https://github.com/samU13/natours-cursonode.git
cd natours-cursonode
```

### 2. Instala las dependencias:

Usa [pnpm](https://pnpm.io/installation) o el gestor de paquetes de tu elección para instalar las dependencias.

```bash
pnpm install
```

### 3. Inicia el servidor de desarrollo:

```bash
pnpm dev
```

1. Abre [**http://localhost:3000**](http://localhost:3000/) en tu navegador para ver el resultado

## Comandos

| Comando      | Acción                                                                              |
| :----------- | :---------------------------------------------------------------------------------- |
| `start`      | Inicia el servidor ejecutando `server.js` en modo producción.                       |
| `dev`        | Inicia el servidor en modo desarrollo con `nodemon` para hot-reloading.             |
| `start:prod` | Ejecuta el servidor en modo producción con la variable de entorno `NODE_ENV`.       |
| `debug`      | Ejecuta `nodemon` con el flag `--inspect` para habilitar la depuración.             |
| `build:js`   | Usa `esbuild` para crear un bundle del archivo `index.js` en `./public/js`.         |
| `watch:js`   | Usa `esbuild` para observar cambios en `index.js` y crear un bundle en tiempo real. |

## Usuario

1. Utiliza este usuario para probar :

<p>   <em>email</em> : admin@natours.io</p>
<p>   <em>password</em> : test1234</p>
