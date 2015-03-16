Docker-compose config for Yii 2 Application Template
===================================
Yii 2 docker is a configuration for easy deployment of yii2 template application.

REQUIREMENTS
------------

Docker and Docker compose

INSTALLATION
------------
Clone this repository. 
~~~
git clone http://github.com/sokrat/yii2-docker.git app
~~~
Clone yii 2 application
~~~
git clone https://github.com/yiisoft/yii2-app-advanced.git app/project
or
git clone https://github.com/yiisoft/yii2-app-basic.git app/project
~~~
Remove ".example" from nginx configuration example filename (docker/nginx/conf.d)

USING
------
For executing commands inside docker container run
~~~
docker-compose run php {command}
~~~
Start docker containers 
~~~
docker-compose up -d
~~~
After start check http://127.0.0.1:8090