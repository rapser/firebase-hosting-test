# Firebase Hosting testing

Mediante un proyecto de ejemplo, publicaremos una web con firebase hosting

## Requisitos

- Node js
- Firebase console
- Cloudflare

## Instalación

Nos dirijimos al Hosting, le damos en crear
Abrimos el terminal y pegamos el codigo para su posterior ejecución

```sh
$ npm install -g firebase-tools
```
Nos pedirá loguearnos con nuestra cuenta google

```sh
$ firebase login
```

Inicializamos firebase en nuestro proyecto.

```sh
$ firebase init
```

Seleccionamos hosting con la barra espaciadora y le damos enter. Luego seleccionamos el proyecto que hemos creado previamente en la consola de firebase.
Creamos una carpeta public para contener el código fuente de nuestra pagina web.

```sh
? What do you want to use as your public directory? public
? Configure as a single-page app (rewrite all urls to /index.html)? No
? Set up automatic builds and deploys with GitHub? No
? File public/index.html already exists. Overwrite? No
```

Finalmente desplegamos nuestro sitio web

```sh
$ firebase deploy
```