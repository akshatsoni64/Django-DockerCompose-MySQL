# Docker Compose Example with Django+MySQL

Simple setup template for deploying django application with MySQL database using docker-compose

##Setup

- Clone the repo
```
git clone 
```

- Jump to project directory
```
cd <dir-name>
```

- Start the container
```
docker-compose up --build
```

- Create the super user
```
docker exec -it <container-id> bash #access the container
python manage.py createsuperuser
```

Start developing upon this boilerplate and the changes will be reflected on the django webserver