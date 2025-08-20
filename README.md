# Greenlight
JSON API for retrieving and managing information about movies. Based on Alex Edwards [Let's Go Further](https://lets-go-further.alexedwards.net/) book.


## Technology Stack
* **Go** as the primary programming language.
* **PostgreSQL** as the relational database.
* **HttpRouter** as the HTTP router.


## API Endpoints
| Method | URL Pattern | Action |
| :--- | :--- | :--- |
| GET | `/v1/healthcheck` | Show application health and version information |
| GET | `/v1/movies` | Show the details of all movies |
| POST | `/v1/movies` | Create a new movie |
| GET | `/v1/movies/:id` | Show the details of a specific movie |
| PATCH | `/v1/movies/:id` | Update the details of a specific movie |
| DELETE | `/v1/movies/:id` | Delete a specific movie |
| POST | `/v1/users` | Register a new user |
| PUT | `/v1/users/activated` | Activate a specific user |
| PUT | `/v1/users/password` | Update the password for a specific user |
| POST | `/v1/tokens/authentication` | Generate a new authentication token |
| POST | `/v1/tokens/password-reset` | Generate a new password-reset token |
| GET | `/debug/vars` | Display application metrics |



