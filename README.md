## SIMPLE GUNICORN APP

* 1 clone this repo
* 2 execute

``
docker build -t flask/hello-world .
``

* 3 then execute in your docker local

``
docker run -p 8003:8003 flask/hello-world
``

By Christian Regner