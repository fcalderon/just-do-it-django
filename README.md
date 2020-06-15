# Simple Django App

## Requirements
* Python 3+
* virtualenv
* Postgres DB (or docker)

## Setup 

```shell script
# init the virtual environment 
$ virtualenv env
$ . .env/bin/activate 

# install dependencies

$ pip install -r requirements.txt
```

## DB with docker

Just run with compose. 

```shell script
$ docker-compose up
```

### Running

```shell script
$ cd justdoit

$ python manage.py runserver
```