# My App Name
Demo App with basic Rest API.

##REST API
List of basic routes :

| Router                  | HTTP | Description           |
|------------------------|------|-----------------------|
| /api/hello?name={name} | GET  | Print hello, {name} ! |

List of user routes :

| Route          | HTTP   | Description                          |
|----------------|--------|--------------------------------------|
| /api/users     | GET    | Get all the users                    |
| /api/users/:id | GET    | Get a single user                    |
| /api/users     | POST   | Create a User                        |
| /api/users/:id | DELETE | Delete a User                        |
| /api/users/:id | PUT    | Update a user with new info          |
| /api/users/:id | PATCH  | Update a user with specific new info |


List of Filter routes :

| Route                    | HTTP | Description               |
|--------------------------|------|---------------------------|
| /api/users?name="{name}" | GET  | Get {name} match in users |
| /api/users?name="{na}"   | GET  | Get {na} like in users    |

***

##Usage

With only npm :
```
npm install
npm start
npm run dev
```

Access the website via https://restfull-api-myapp.herokuapp.com/ or API via https://restfull-api-myapp.herokuapp.com/api