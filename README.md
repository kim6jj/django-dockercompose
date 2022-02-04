# django-dockercompose

- django app (website) deployed using docker-compose directly on a linux ami on aws ec2

- configure project for deployment
- media/static files (run WSGI web service gateway interface to handle static/media files); reverse proxy (Nginx) in front of Django app which serves all requests with /static from filesystem and passes the rest to WSGI service 
- ![image](https://user-images.githubusercontent.com/1181741/152580155-5e9235f0-39c2-46c3-a649-726bf7d6ea7b.png)
- run migrations 
- and push updates to the app
