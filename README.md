![](https://www.teguharief.com/img/teguh-arief.png)

# Go Gin MongoDB

a CRUD API with Go's Gin library using MongoDB.

## Installation

```
git clone https://github.com/teguharifudin/Go-Gin-MongoDB.git
```
```
cd Go-Gin-MongoDB
```

### Testing

```
go run main.go 
```

## Postman

POST http://localhost:6000/user
```
{
    "name": "Teguh",
    "location": "Bandung",
    "title": "Programmer"
}
```

GET http://localhost:6000/users

PUT http://localhost:6000/user/6666a4e25c83ead7c00db79b
```
{
    "name": "Arief",
    "location": "Bandung",
    "title": "Programmer"
}
```

GET http://localhost:6000/user/6666a4e25c83ead7c00db79b

DELETE http://localhost:6000/user/6666a4e25c83ead7c00db79b
