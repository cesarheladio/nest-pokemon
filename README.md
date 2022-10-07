<p align="center">
  <a href="http://nestjs.com/" target="blank"><img src="https://nestjs.com/img/logo-small.svg" width="200" alt="Nest Logo" /></a>
</p>

# Ejequtar desarrollo

1. Clonar el repositorio
2. Ejecutar
```

yarn install
```
3. Tener Best CLI instalado
```

npm i-g @nestjs/cli
```

4. Lenvantar la base de datos
```

docker-compose up -d
```

5. Clonar el archivo __.env.template__ y renombrar la compia a __.env__

6. llenar las variables de entorno definidas en el __.env__

7. Ejecutar la aplicacion en dev:
```
yarn start:dev
```

9. Reconstruir la base de datos con seed
```

http://localhost/api/v2/seed
```

## Stack usado
* MongoDB
* Nest