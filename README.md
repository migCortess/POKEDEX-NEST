# POKEDEX-NEST
TEST BACKEND SERVER USING NEST AND MONGODB

<p align="center">
  <a href="http://nestjs.com/" target="blank"><img src="https://nestjs.com/img/logo-small.svg" width="200" alt="Nest Logo" /></a>
</p>

#Ejecutar en Desarrollo

1. Clonar en Repositorio
2. Ejecutar
```
yarn install
```

3. Tener Nest CLI instalado
```
npm i -g @nest/cli
```

4. Levantar la Base de Datos
```
docker-compose up  -d
```

5. Clonar el archivo  __.env.template__ y renombrar la copia a __env__.

6. Reconstruir la DB con la semilla
```
http://localhost:3000/api/v2/seed
```

7. Ejecutar la aplicación en dev: 

```
yarn start:dev
```
8. Reconstruir la base de datos
```
http://localhost:3000/api/v2/seed
```

##Stack Usado
* MongoDB
* Nest
