<p align="center">
  <a href="http://nestjs.com/" target="blank"><img src="https://nestjs.com/img/logo-small.svg" width="200" alt="Nest Logo" /></a>
</p>

```
docker exec -it <container-id> psql -U <username> -d <database-name>
```

# Dev

1. Clonar proyect
2. Copiar el ```.env.template``` y renombrar a ```.env```
3. Ejecutar

```
yarn install
```

4. Levantar la imagen (Docker desktop)
```
docker-compose up -d
```

5. Levantar el backend de nest
```
yarn start:dev
```

6. Visitar el sitio
```
localhost:3000/graphql
```

7. Ejecutar la __"mutation"__ executeSeed, para llenar la base de datos con información