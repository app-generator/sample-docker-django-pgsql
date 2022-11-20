## How to start with docker

## ✨ Start the app in Docker

> **Step 1** - Download the code from the GH repository (using `GIT`) 

```bash
$ git clone https://github.com/app-generator/django-material-kit.git
$ cd django-material-kit
```

<br />

> **Step 2** - Start the APP in `Docker`

```bash
$ docker-compose up --build 
```


```bash
$ docker-compose run --rm appseed-app python manage.py makemigrations
$ docker-compose run --rm appseed-app python manage.py migrate
```


Visit `http://localhost:5085` in your browser. The app should be up & running.

<br />
