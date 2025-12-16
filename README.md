# help_desk2
api
Sistema HelpDesk - Frontend + API
Proyecto Mesa de Ayuda (HelpDesk)
Incluye Frontend (HTML, CSS, JS) y consumo del API REST.

1. Frontend
login.html

<form>
Email, contraseña y botón de login.
Consume POST /auth/login

dashboard.html

Gestión de usuarios.
Consume GET /users y POST /users

styles.css
Estilos generales del sistema
2. API HelpDesk
Autenticación

POST /auth/login
Body:
{
 email,
 password
}

Usuarios

GET /users
POST /users

Casos

GET /cases
POST /cases
PUT /cases/:id

Reportes

GET /reports/summary

