### DJReact

Source code for a blog post I wrote on how to use Yarn Workspaces with Django and React.

You can read the article here:

Running the Django backend:

```bash
# Create a Python3 virtual environment

$ python -m venv .venv
$ source .venv/bin/activate

# Running the backend
$ python manage.py runserver
```

Running the React frontend:

```bash
# Installing the dependencies
$ yarn workspace client install

# Running the frontend:
$ yarn workspace client start
```
