# CRUD CON ANGULAR

## EJECUTAR EL FRONTEND

* cd productos Entrar al directorio productos
* npm install Instalar dependencias (node_modules)
* npm run start Correr servicio

[![Screenshot-1.png](https://i.postimg.cc/tT0yHg9Y/Screenshot-1.png)](https://postimg.cc/mcSKYBzs)

[![Screenshot-2.png](https://i.postimg.cc/kgkL2hzH/Screenshot-2.png)](https://postimg.cc/87mZ3w1d)

## Configuracion dockerfile

[![Screenshot-3.png](https://i.postimg.cc/5tBK69wH/Screenshot-3.png)](https://postimg.cc/d70jfYNv)

## Configuracion docker-compose.yml

[![Screenshot-4.png](https://i.postimg.cc/BbLxPNdh/Screenshot-4.png)](https://postimg.cc/q6rt9cBn)

### Utilizacion de docker con utilidades

* Instalamos dependencias
** docker-compose run --rm npm install

* Ejecutar proyecto
** docker-compose up -d --build server

* Acceder al CLI de angular
** docker-compose run -rm ng

* Generar un nuevo componente en angular
** docker-compose run -rm ng generate component crear-producto
