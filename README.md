# FLASK BOOKMARK API USING MARSHMALLOW

![python badge](https://img.shields.io/badge/Python-3.8-green)  
![Flask badge](https://img.shields.io/badge/Flask%20-2.0.1-gray)  
![MarshMallow badge](https://img.shields.io/badge/MarshMallow%20-13.3-blue)  
![Pytest badge](https://img.shields.io/badge/pytest-6.2.5-red) 


This project tries to illustrate the concept of object validation in marshmallow.
It uses SQLAlchemy to manage models, SQLite for data storage, Marshmallow for 
data serialization,deserialization, and validation and tests created with
pytest. Finally, it incoporates Circle CI for Continuous Intergration.

## Instalation
---
```shell
python -m venv venv
source venv/bin/activate
pip install -r requirements.txt
```

## Running the Application
---
```shell
python src/app.py
```

## Running tests
---
```shell
python -m pytest -s
```
