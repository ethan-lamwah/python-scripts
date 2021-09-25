## Using Virtual Environments

View [virtualenvwrapper][1] for more commands and documentation

```python
pip install virtualenvwrapper-win
```

Create a new virtual enverionmen.
```python
mkvirtualenv env [-a project_path] [-r requirements_file] ENV_NAME
```

## Django
### Create a new Django project [myproject] in command line
```
django-admin startproject myproject
``` 

### Create a new application [myapp]
```
python manage.py startapp myapp
```

### Run web server

```
python manage.py runserver
```

> Ignore the warnings about  "18 unapplied migration(s)" at this point. 

Onece the server is running, you can view the site by navigating to the following URL on the local web browser: http://127.0.0.1:8000/


<!-- URL below -->
[1]:https://virtualenvwrapper.readthedocs.io/en/latest/command_ref.html#managing-environments