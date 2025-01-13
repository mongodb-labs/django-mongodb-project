# Django MongoDB Project Template

This is the starter template for the Django-MongoDB Backend. In order to use, with your version of `django-mongodb-backend` and `django`:

* Find your Django version.
* Based on your Django version, provide that in the link defined below.

## Create the Django Project
From your shell, run the following command to create a new Django project replacing the `{{ project_name }}` and `{{ version }}` sections. 

```bash
django-admin startproject {{ project_name }} --template https://github.com/mongodb-labs/django-mongodb-project/archive/refs/heads/{{ version }}.x.zip
```

Below is an example:

For a project name `5_0_exmaple` that runs on `django==5.0.*`:

```bash
django-admin startproject 5_0_example --template https://github.com/mongodb-labs/django-mongodb-project/archive/refs/heads/5.0.x.zip
```
