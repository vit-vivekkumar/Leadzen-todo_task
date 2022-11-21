Create a simple TODO web App with following features
• Add Task
• Delete Task
• Mark as Completed
• List of Tasks
• List of Completed Tasks
• List of Pending Tasks

## Used Tools

- Django, ReactJS

#

# How to Run Project

## Download Codes


## Install Backend Requirements

```
pip install  requirements. txt
```


## Install Frontend Dependencies

```
cd frontend
```
todo_frontend
```
npm install

```

## Migrate Backend Models

```
cd ..
cd backend
```

```
python manage.py makemigrations todo
```

```
python manage.py migrate
```

## Add Super User

```
python manage.py createsuperuser
```

## Run Django Server

```
python manage.py runserver
```

## Run FrontEnd

open new terminal in `todo_frontend` directory and run this command.

```
npm start
```

## Open On Browser

App Page
[localhost:3000]

Django Admin Page
[127.0.0.1:8000/admin]
