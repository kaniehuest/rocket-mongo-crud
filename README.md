# CRUD with Rocket and MongoDB

CRUD using rust web framework "Rocket" and MongoDB as database.

# How to run

### Install cargo

You can install it with [rustup](https://rustup.rs/).

### Create the .env file

You must create a .env file and edit it with your MongoDB URI, you can see an example in the `.env.example` file.

### Run the app

```
cargo run
```

# Routes

### Create an user

Route -> `/user`
Method -> POST

Body

```json
{
  "name": "John Doe",
  "location": "Street #123",
  "title": "This is a title"
}
```

### Get a user

Route -> `/user/<id>`
Method -> GET

### Update a user

Route -> `/user/<id>`
Method -> PUT

### Delete a user

Route -> `/user/<id>`
Method -> DELETE

### Get all users

Route -> `/users`
Method -> GET
