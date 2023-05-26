#  Projeto Alura - Alura Space

## Description

A project where we learned about best practices with django.

## Starting

To run the project, you will need to install the following programs:

- [Python: Required to create the project](https://www.python.org/downloads/)
- [VS Code: For project development](https://code.visualstudio.com/)

## ⌨️ Development

Use Gitpod, a free online dev environment for GitHub.

[![Open in Gitpod](https://gitpod.io/button/open-in-gitpod.svg)](https://gitpod.io/#https://github.com/Suspir0n/alura_space.git)

Or use code locally using:
```
$ cd "directory of your choice"
$ git clone https://github.com/Suspir0n/alura_space.git
```

### Construction

To build the django application, execute the commands below:

```
$ pip install -r requirements.txt
```

These are the requirements.txt dependencies:

```
asgiref==3.7.1
Django==4.2.1
python-dotenv==1.0.0
sqlparse==0.4.4
tzdata==2023.3
```

## Project structure
```
 - Alura Space/
   - galeria
     - migrations/
        - __init__.py
     - __init__.py
     - admin.py
     - apps.py
     - models.py
     - tests.py
     - urls.py
     - views.py
   - setup/
     - static/
       - assets/
       - styles/
       - __init__.py
       - settings.py
       - urls.py
       - asgi.py
       - wsgi.py
   - static/
     - admin/
     - assets/
     - styles/
   - templates/
     - galeria/
        - partials/
            - _footer.html
            - _menu.html
        - base.html
        - index.html
        - imagem.html
   - .gitignore
   - manage.py
   - README.md
   - requirements.txt
```

## Configuration

To execute the project, it is necessary to use VsCode or an IDE of your preference, so that it identifies the dependencies necessary for execution in the repository. Once the project is imported, it will be possible to test its functionality in real time.

## Contributions

Contributions are always welcome! I hope I have helped someone in need.

## 🔓 License
MIT © [Evandro Silva](https://www.linkedin.com/in/suspir0n/)