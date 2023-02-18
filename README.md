# flask_login_authentication

## Installation steps

* Setup the virtual environment

```virtualenv -p python3 .venv```

* Activate the virtual environment

```.venv/Scripts/activate```

* Install Flask,Flask-Login,Flask-SQLAlchemy

```python -m pip install flask```

```python -m pip install flask-login```

```python -m pip install flask-sqlalchemy```

## Setting Up the database

* In the terminal,make use of the python shell
```
from project import db, create_app, models
db.create_all(app=create_app()) 
```

## Start the server

```flask run```

**Note:The server runs on http://127.0.0.1:5000

## Demo video

[click here](https://drive.google.com/file/d/12bB2nllKO3zLGGMzV6pLPNANzn4Yh6KD/view?usp=share_link)

