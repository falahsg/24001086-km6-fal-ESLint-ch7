# Binar - Testing ESLint Challenge CH 07

Menerapkan ESLint pada kode yang ditulis, Melakukan unit testing pada kode yang ditulis, Melakukan deployment

# Setup & Running Server

    1. create `.env` file and setup credential `.env`
    2. run `npm install`
    3. run `db:create` to create `development` environtment database
    4. run `db:migrate` to migrate the table
    5. run `db:seed` to populate the database
    6. `run npm run` start to start the server

## Server Routing

| Page                  | Route            | Default Route                         |
| --------------------- | ---------------- | ------------------------------------- |
| Documentation Swagger | `/documentation` | http://localhost:{PORT}/documentation |
