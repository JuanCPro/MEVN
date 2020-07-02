# MEVN
En este repositorio encontrarán 2 carpetas sistema y sistema/vue. 
Dentro de sistema se encuentra la parte del Back-end y en sistema vue la parte del front-end.

# sistema

- Controllers: Los controladores de los modelos
- Middlewares: Autenticación mnediante tokens
- models: Modelos para la base de datos y un index.js que contiene todos los modeos
- public: En este caso solo tiene un index.htnml
- routes: Mapeo de las rutas mediante express-promise-router y un index.js que contiene todos los mapeos
- services: Controla (Codifica, actualiza, o decodifica) los tokens (utiliza jwt)

# Sistema Vue
Los más interesante, es el uso de axios, vuerouter y vuex
- Router.js: Se utilzia Vue-router
- Store.js : Se utiliza Vuex
- Dentro de la carpeta Components hay componentes que utilizan axios, precisamente el marte de metodos (En especial el login.vue)

# Corriendo el proyecto
Para correr el proyecto de lado del servidor, deberán hacer 
```sh
$ cd /sistema
$ npm install 
$ npm run dev
```

Para correr el proyecto de lado del cliente, deberán hacer 
```sh
$ cd /sistemavue
$ npm install 
$ npm run serve
```

# Nota
Ignoren el material desing, así venía el tutorial xd
Por lo que les pido por favor que ignoren la parte de html de los .vue
