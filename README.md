### Eng: The final project is a test of our knowledge acquired throughout the bootcamp, where we collaborate with other departments such as UX/UI, Data Science, and Cybersecurity. We form a team of three people in the Full Stack department.

### Esp: El proyecto final es una prueba de nuestros conocimientos adquiridos durante todo el bootcamp, donde colaboramos con otros departamentos como UX/UI, Data Science y Ciberseguridad. Formamos un equipo de tres personas en el departamento de Full Stack.

## Original repository: https://github.com/JorgePeju/tripulacion_back

# Enlace al repositorio front:
````
https://github.com/dorian-rose/tripulacion_front
````

# Enlace del despliegue de la API:

````
- https://h2ohback.onrender.com/
```` 
## Base de datos de entradas:

- Obtener todas las entradas:
````
- GET: https://h2ohback.onrender.com/api/v1/entries/
````  

- Obtener una entrada por ID o un usuario por su ID si existe su entrada:
````
- GET: https://h2ohback.onrender.com/api/v1/entries/:id
```` 
- Crear una entrada:
````
- POST: https://h2ohback.onrender.com/api/v1/entries/
````  

- Editar una entrada por id:
````
- PUT: https://h2ohback.onrender.com/api/v1/entries/:id
````
- Eliminar una entrada por id:
````
- DELETE: https://h2ohback.onrender.com/api/v1/entries/:id
````  
-Eliminar todas las entradas de un usuario por id:
 
## Base de datos de los usuarios:
- Obtener todos los usuarios:
````
- GET: https://h2ohback.onrender.com/api/v1/auth/
````
- Obtener un usuario por ID:
````
- GET: https://h2ohback.onrender.com/api/v1/auth/:id
````
- Crear un usuario:
````
- POST: https://h2ohback.onrender.com/api/v1/auth/register
````
- Editar un usuario por id:
````
- PUT: https://h2ohback.onrender.com/api/v1/auth/:id
````
- Eliminar un usuario por id:
````
- DELETE: https://h2ohback.onrender.com/api/v1/auth/users
````

## Endpoints de autentificación:

- Logear con un usuario:
````
- POST: https://h2ohback.onrender.com/api/v1/auth/login
````
- Delogear con un usuario:
````
- GET: https://h2ohback.onrender.com/api/v1/auth/logout
````
- Recuperar la contraseña de un usuario:
````
- POST: https://h2ohback.onrender.com/api/v1/auth/reset
````
