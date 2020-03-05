# Django Portfolio App

Django application to manage your basic portfolio which demonstrates CRUD operations

## Setup

### Install Django:
```bash
pip install Django
```

### Perform database migration:
```bash
python manage.py check
python manage.py migrate
```

## Run Development Server

```bash
python manage.py runserver
```
Public endpoint is at http://localhost:8000/polls/

Admin endpoint is at http://127.0.0.1:8000/admin/, `user: admin`, `password: qazwsxedc`

## Testing

### Run tests:
```bash
python manage.py test
```

```bash
Creating test database for alias 'default'...
System check identified no issues (0 silenced).
..........
----------------------------------------------------------------------
Ran 10 tests in 0.025s

OK
Destroying test database for alias 'default'...
```

### Run tests with coverage:
```bash
pip install coverage
coverage run --source='.' manage.py test
```

### Check coverage report:
```bash
coverage report
```
