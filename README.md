# NestJS API with Prisma and MySQL

## Setup

1. Install dependencies:
```bash
npm install
```

2. Start MySQL with Docker:
```bash
docker-compose up -d
```

3. Generate Prisma Client:
```bash
npx prisma generate
```

4. Run migrations:
```bash
npx prisma migrate dev --name init
```

5. Start the application:
```bash
npm run start:dev
```

## API Documentation

Swagger UI: http://localhost:3000/api

## Endpoints

- `POST /users` - Create user
- `GET /users` - Get all users
- `GET /users/:id` - Get user by ID
- `PATCH /users/:id` - Update user
- `DELETE /users/:id` - Delete user
