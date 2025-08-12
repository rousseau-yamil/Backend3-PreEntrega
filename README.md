# Pre Entrega

##Generacion de 50 usuarios
```GET /api/mocks/mockingusers``` 

##Generacion de 50 mascotas
```GET /api/mocks/mockingpets```

##Generar usuarios y mascotas guardando los registros en base
```POST /api/mocks/generateData```
EN BODY introducir cantidad de usuarios y mascotas que se generaran y guardaran en la base de datos 
```JSON
{ 
  "users": 2, "pets": 1
}
```

### Comprobacion de registros
#### OBTENER USUARIOS DE LA BASE DE DATOS
```GET /api/mocks/users```

#### OBTENER MASCOTAS DE LA BASE DE DATOS
```GET /api/mocks/pets```
