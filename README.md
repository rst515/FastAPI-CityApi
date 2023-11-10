# CityAPI
### A simple FastAPI for cities 
Source: [Intro to FastAPI - The Best Way to Create APIs in Python?
](https://www.youtube.com/watch?v=kCggyi_7pHg)

![FastAPI](https://img.shields.io/badge/FastAPI-005571?style=for-the-badge&logo=fastapi)
## Setup
To use this project
1. Clone the repository.
2. Install the project dependencies using `pip install -r requirements.txt`

## Run the app
Show the app in the browser (--reload gets live changes)
`hypercorn main:app --reload`

## View API documentation
There are two options:
1. append `/docs` to the url see Swagger documentation (e.g. http://127.0.0.1:8000/docs)
2. append `/redoc` to the url see Redoc documentation (e.g. http://127.0.0.1:8000/redoc)

The endpoints can be used to GET, POST and DELETE cities:
```
GET /cities
GET /cities/{city_id}
POST /cities
DELETE /cities/{city_id}
```