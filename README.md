## Django Polls Application

This application contains a questions and answers to make a polls.

## Requirements

The application requires

- Python 3.6 or newer
- Django 2.1.2 or newer
- Python add-on modules as in [requirements.txt](requirements.txt)

## How to Run

Use Python3 and Django2 to manage and runserver.

## Installation

### 1. Install Python 3.6 or newer

Download : https://www.python.org/downloads/

### 2. How to run

1.  Clone this Repository and Change directory

```
git clone https://github.com/mark47546/django-polls.git
```

```
cd django-polls
```

2. Install Requirements

```
pip3 install -r requirements.txt
```

3. Create .env

```
vi .env
```

4. Add these to .env

```
SECRET_KEY = 'your_secret_key'
DATABASES =  your_database
TIME_ZONE =  'your_time_zone'
DEBUG = True
```

5. Migrate

```
python3 manage.py migrate
```

6. Runserver

```
python3 manage.py runserver
```
