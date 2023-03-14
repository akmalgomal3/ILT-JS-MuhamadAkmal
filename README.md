# ILT-JS-MuhamadAkmal

prerequisites
Node.js version >= 12.x

Run the application
npm install : install dependencies
npm run start : to run the application
npm run start:dev : to run the application in development mode (hot reloading)

Create the simple RESTFul API using Node.js Natively and Hapi Framework with the specification:

| Method | Path          | Response Code | Body | Description         |
| ------ |---------------| ------------- | ---- |---------------------|
| POST   | /contacts     | 201 | JSON | Create new contacts |
| GET    | /contacts     | 200 | JSON | List of contacts    |
| DELETE | /contacts/:id | 200 | JSON | Delete contacts     |

User data structure:

```json
{
    id: 1,
    name: 'Yudi Just In Case',
    email: 'yudiyudi@example.com',
    phone: "08080888",
}
```
Server options:
 - `port`: 3000
 - `host`: localhost
