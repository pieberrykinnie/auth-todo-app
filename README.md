# auth-todo-app

To-do list application with base HTML + CSS + JavaScript with fetch API for frontend, and Node.js + Express for backend. Use a local SQLite database for data persistence, and `bcryptjs` + `jsonwebtoken` for JWT authentication. Adapted from Smoljames' tutorial [Backend Full Course](https://youtu.be/9BD9eK9VqXA?si=trWojZUKQFdGk4Wg).

## Quickstart

Create an `.env` file with the following:

```text
JWT_SECRET="your_jwt_secret_key"
PORT=5000
```

Install the required packages using `npm`:

```bash
npm install
```

Run the development server then navigate to `http://localhost:5000/`:

```bash
npm run dev
```

Play around with the website; note that the database will be wiped when the server resets. Alternatively, use Postman or REST Client on your favorite text editor to test out the backend functionalities. Examples can be found in the [todo-app.http](./todo-app.http) file for syntax.
