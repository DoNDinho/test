# GenerateEncryptToken
_Microservicio para generar y encriptar token_

## Herramientas necesarias 🛠️
* [NPM](https://www.npmjs.com/) - Sistema gestión paquetes Node
* [Node JS Version 12](https://nodejs.org/en/blog/release/v12.13.0/) - Runtime Multiplataforma
* [Postman](https://www.postman.com/) - Cliente para peticiones HTTP

### Instalación 🔧
_Para instalar dependencias ejecute el siguiente comando_
```
$ npm install
```
_Crea un archivo .env con las siguientes variables:_
* **PORT** - Puerto del servidor
* `FIRMATOKENJWT`: Firma del token JWT
* **DURACIONTOKENJWT** - Duracion token JWT en segundos
* **FIRMATOKENJWE** - Firmta token JWE

_Ejecuta el servidor:_
```
$ npm start
```

_test_
```json
{
  "name": "Diego",
  "age": 24
}
```

## Autor ✒️
* **Diego Flores** - Desarrollador [DoNDinho](https://github.com/DoNDinho)
