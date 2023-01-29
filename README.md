## migrate
php artisan migrate

## JWT
-> php artisan jwt:secret
SECRET GENERATE jwt-auth secret [V0dqKBIpitqYZtRqA77ziPoB9eCyd1xVRoKALqCPk6NQC3gfN8SS7Y7k4I6bwYM1] set successfully.

POST : http://127.0.0.1:8000/api/register
Body : {
    "name" : "dayanna neyra",
    "password" : "Neyra123!",
    "password_confirmation" : "Neyra123!",
    "email" : "dneyra@developer.com"
}

POST : http://127.0.0.1:8000/api/login
Body : {
    "email" : "artyom@developer.com",
    "password" : "tutofox123"
}

POST: http://localhost:8000/api/user
Authorization Bearer Token : <TOKEN>