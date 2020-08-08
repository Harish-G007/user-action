
## Installation

cd user-action
```
I used pipenv to create a virtual environment, so you install pipenv globally on your computer:
```bash
pip install pipenv
```

Create a new virtual environment:
```bash
pipenv shell
```

Next, install required packages stored in the ``Pipfile.lock`` file using the ``sync`` command.
```bash
pipenv sync
```

Then you enter the app directory
```bash
cd django_project
```

After that, you run your migrations:
```bash
python manage.py makemigrations
python manage.py migrate
```

Finally, run the app
```bash
python manage.py runserver
```


