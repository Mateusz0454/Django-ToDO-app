# Django ToDo app

## Screenshots

![ToDo App Screenshot](https://github.com/Mateusz0454/Django-ToDO-app/blob/005d891ff517b1d6bd6a50e90d2c17e18374d256/staticfiles/screen.PNG?raw=true)

## Features

- adding a task
- deleting a task
- displayed task name and full date of creation
- CRUD operations
- possibility to add a status (done/not done)
- possibility of application development
  
## Tech
- Python
- Django

### Setup

To get this project, download in zip or  run the following command inside your git enabled terminal:

```bash
$ git clone https://github.com/shreys7/django-todo.git
```

You will need the Django library installed on your computer for this, for example via pip:

```bash
$ pip install django
```

After downloading django, navigate to the cloned repo directory and run the following command

```bash
$ python manage.py makemigrations
```

This will create all the migration files required to run this application.

Run the following command to apply changes:
```bash
$ python manage.py migrate
```

The last step is to create our superuser. In the teminal, type:

```bash
$ python manage.py createsuperuser
```
Start the server by following command

```bash
$ python manage.py runserver
```

## Author

- [@Mateusz0454](https://www.github.com/Mateusz0454)
