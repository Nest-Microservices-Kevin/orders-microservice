<p align="center">
  <a href="http://nestjs.com/" target="blank"><img src="https://nestjs.com/img/logo-small.svg" width="200" alt="Nest Logo" /></a>
</p>

# Orders MicroService

1. Clonar el proyecto
2. Crear un archivo `.env` basado en el archivo `.env.template`
3. Levantar la base de datos con
```
docker compose up -d
```
4. Ejecutar migración de prisma `npx prisma migrate dev`
5. Levantar el proyecto con `npm run start:dev`