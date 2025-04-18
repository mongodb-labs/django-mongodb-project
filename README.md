# Django MongoDB Backend - Project Template

This is a Django project starter template for the Django MongoDB Backend.
In order to use it with your version of Django: 

- Find your Django version. To do so from the command line, make sure you
  have Django installed and run:

```bash
django-admin --version
>> 5.2
```

## Create the Django project

From your shell, run the following command to create a new Django project
replacing the `{{ project_name }}` and `{{ version }}` sections. 

```bash
django-admin startproject {{ project_name }} --template https://github.com/mongodb-labs/django-mongodb-project/archive/refs/heads/{{ version }}.x.zip
```

For a project named `5_2_example` that runs on `django==5.2.*`
the command would look like this:

```bash
django-admin startproject 5_2_example --template https://github.com/mongodb-labs/django-mongodb-project/archive/refs/heads/5.2.x.zip
```
