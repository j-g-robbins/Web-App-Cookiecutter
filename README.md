# Webapp-Quickstart
Web app cookiecutter using Docker containers.

This is the most basic you can get with a full stack cookie cutter on python and react.

## Setup
Assuming you have Python and npm installed,

1. Clone the repo 

```
git clone git@github.com:j-g-robbins/webapp-quickstart.git
```

2. Navigate into the project: 

``` 
cd webapp-quickstart 
```

3. Populate the .env file with secret values:

```
SECRET_KEY='...'
DB_PASSWORD='postgres'
```
4. Run the app:

```
docker compose build
docker compose up
```
5. Check it's all working

```
Frontend: http://localhost:3000/
Backend: http://localhost:8000/
```

## Infrastructure
#### Frontend 
- Typescript, React
#### Backend
- Python, Django
#### API
- Django Rest Framework.
#### Database
- PostgreSQL
