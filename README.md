## This repository was made in educational purposes, in order to find out how symfony routing works.

To run app:

> ./console server:run 0.0.0.0:8000

Then open http://localhost:8000

Routes are done:
* http://localhost:8000
* http://localhost:8000/api/v1/dogs
* http://localhost:8000/api/v1/dogs/{id}
* http://localhost:8000/api/v1/fogs
* http://localhost:8000/api/v1/fogs/{id}
* http://localhost:8000/api/v1/cats
* http://localhost:8000/api/v1/cats/{id}

And special route for subdomain. You need to copy .env_dist to .env and fill it with your own hostname. Then open http://sub.{your_host_name}:8000
