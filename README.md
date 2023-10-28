
# Newspaper App

The Newspaper app is an online site where journalists can post articles on daily news.


## Features

- Uses Custom User Model
- Users can perform all CURD (Create, Update, Read, Delete) operations.
- Users can log in, log out and, sign up for a new account.
- Added permissions and authorization using django mixins.
- Users can post comments on individual articles.

## Run Locally

Clone the project

```bash
  git clone https://github.com/suraj-py/Newspaper-App.git
```

Go to the project directory

```bash
  cd Newspaper-App
```

Create virtual environment

```bash
  pipenv shell
```

If you don't have pipenv, install it using pip

```bash
  pip3 install pipenv
```

Install dependencies, this will install all require packages from Pipefile.lock

```bash
  pipenv sync
```

Start the server

```bash
  python manage.py runserver
```

## Acknowledgements

 - [Django for Beginners](https://djangoforbeginners.com/)


