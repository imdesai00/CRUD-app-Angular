
# Angular CRUD with LOGIN/SIGNUP ALL FUNCTIONALITY

        This Angular project is a complete solution for building a CRUD (Create, Read, Update, Delete) application with robust authentication and authorization features. It includes functionalities like user registration, login, forget password, password hashing, and role-based access control (RBAC), ensuring secure and efficient management of data.


## Features

- Authentication: Users can register and log in securely using their email address and password. Authentication is implemented using JWT (JSON Web Tokens), providing a stateless and scalable solution.

- Authorization: Role-based access control (RBAC) is implemented to restrict access to certain functionalities or resources based on user roles. Administrators can manage user roles and permissions.

- Forget Password: Users can reset their passwords if they forget them. A secure reset password functionality is implemented to ensure user account security.

- Password Hashing: User passwords are securely hashed using a strong cryptographic algorithm along with a unique salt. This ensures that passwords are not stored in plaintext and are protected from security threats like brute-force attacks.

- CRUD Operations: The application supports CRUD operations for managing data. Users with appropriate permissions can create, read, update, and delete records as nee


## Technologies Used

**ASP.NET Core:** The primary framework for building web applications and APIs.

**C#:** The programming language used for backend logic and API.

**JWT (JSON Web Tokens):** Used for secure token generation and authentication.

**SMTP:** Simple Mail Transfer Protocol for sending emails

**Swagger UI:** A tool to document and test APIs.

**PostgreSQL:** A lightweight, file-based database used for local development and testing.

## Deployment

To Clone this Project

```bash
    git clone https://github.com/imdesai00/CRUD-app-Angular.git
```

Install Dependency

```bash
    npm install
```

Install Dependency

```bash
    ng serve
```

you need ASP DOTNET CORE WEB API to successfully run this project and you can also find out api in git repo.

