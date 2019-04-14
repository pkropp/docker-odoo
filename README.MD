## Odoo ERP

``git clone https://github.com/pkropp/docker-odoo.git``

``cd docker-odoo``

chose between
``docker-compose up`` (just needs Crtl + c to stop the running container)

and
``docker-compose up -d`` (for detached mode)
``docker-compose down`` (for stopping container - remember to run command in the same folder where you started it - includes the docker-compose.yml file)

open ``localhost`` in your browser (remember you should have host file editor or edited your hosts file (located C:\windows\system32\etc\hosts))

Feedback: philipp.kropp@gmail.com

docker cleanup options:

``docker image prune``

``docker image prune -a``

``docker volume prune``