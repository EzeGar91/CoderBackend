# Deno REST API
Una simple REST API de ejemplo con funciones CRUD usando Deno y Oak

## Iniciar localmente
```
deno run --allow-net server.ts
```

# Endpoints

Get All users
```
GET      /users
```

Get a single User by Id
```
GET      /users/:id
```

Create a new User
```
POST     /products
```

Update an existing User by Id
```
PUT      /users/:id
```

Delete an existing User by Id
```
DELETE   /users/:id
```