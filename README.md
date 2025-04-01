# Requerimientos
##🔐 Autenticación
- Endpoint: POST /register y POST /login
- Guardar email, password (con hash)
- Autenticación con JWT (guardar token)
- Usar middleware auth para proteger /cars
## 🚘 Listado de autos
- GET /cars devuelve un array de autos
- GET /cars?brand=Toyota filtra por marca
- Seedear con al menos 5 autos, marcas variadas
## 🧱 Base de datos
- Incluir migraciones y seeds (con scripts npm)
## ⚙️ Tech Stack
- Node.js
- Express
- Autenticación con JWT
- ORM: Sequelize, Prisma o similar
- Base de datos: SQLite para simplicidad (ideal para correr local rápido)
## Entrega
- Devolver POSTMAN o listado de cURLS con ejemplos.
- README.md actualizado con pasos para instalar, versiones, comandos útiles.
