# Backend-code
# Routes

### Services

```
GET      /api/v1/services
GET      /api/v1/services/:id
POST     /api/v1/services
PUT      /api/v1/services/:id
DELETE   /api/v1/services/:id
PUT gallery-images : /api/v1/services/gallery-images/:id
GET featured services: /api/v1/services/get/featured/:count
GET services count: /api/v1/services/get/count
```

### Users

```
GET      /api/v1/users
GET      /api/v1/users/:id
POST     /api/v1/users
PUT      /api/v1/users/:id
DELETE   /api/v1/users/:id
GET users count: /api/v1/users/get/count
```

#### Register new user

```
POST     /api/v1/users/register
```

#### Login user

To login the user and get the auth token:

```
POST     /api/v1/users/login
```
