# [Django Dynamic API](https://github.com/app-generator/django-dynamic-api) `Sample`

Minimal **Django** project with `Docker` support - actively supported by [AppSeed](https://appseed.us/) via `Email` and `Discord`.

> Features - see **[video](https://www.youtube.com/watch?v=nPQMUafTrNY)** presentation

- ✅ `Up-to-date Dependencies`
- ✅ `Docker`
- ✅ Integrates [Dynamic API Library](https://github.com/app-generator/django-dynamic-api) Library for Django

<br />

## ✨ Start the app in Docker

> 👉 **Step 1** - Download the code from the GH repository (using `GIT`) 

```bash
$ git clone https://github.com/app-generator/core-django-dyn-api.git
$ cd core-django-dyn-api
```

<br />

> 👉 **Step 2** - Start the APP in `Docker`

```bash
$ docker-compose up --build 
```

Visit `http://localhost:5085` in your browser. The app should be up & running.

<br />

## Manual Build 

> 👉 Download the code  

```bash
$ git clone https://github.com/app-generator/core-django-dyn-api.git
$ cd core-django-dyn-api
```

<br />

> 👉 Install modules via `VENV`  

```bash
$ virtualenv env
$ source env/bin/activate
$ pip install -r requirements.txt
```

<br />

> 👉 Set Up Database

```bash
$ python manage.py makemigrations
$ python manage.py migrate
```

<br />

> 👉 Start the app

```bash
$ python manage.py runserver
```

At this point, the app runs at `http://127.0.0.1:8000/`. 

<br />

![Django Dynamic API - DRF Interface (open-source tool).](https://user-images.githubusercontent.com/51070104/197497608-8c739370-e7e1-4144-a070-25d51c5a6067.jpg) 

<br />

---
[Django Dynamic API](https://github.com/app-generator/django-dynamic-api) `Sample` - Minimal **Django** starter provided by **[AppSeed](https://appseed.us/)**
