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

## Screenshots

### Home page

![image](https://user-images.githubusercontent.com/88674671/219829188-e195fc40-8087-4c50-8ccf-4008c60e45b4.png)

### Login page

![image](https://user-images.githubusercontent.com/88674671/219829118-0f1b74fa-bbc9-48e8-9d0e-ddec614121c4.png)

### Signup page 

![image](https://user-images.githubusercontent.com/88674671/219829147-50cc6578-fe49-4a7e-9123-d82548820226.png)

### Profile page

![image](https://user-images.githubusercontent.com/88674671/219829174-2bb2c20e-ed85-4a01-92a7-a6d3659d7ba8.png)

## Demo video

[click here](https://drive.google.com/file/d/12bB2nllKO3zLGGMzV6pLPNANzn4Yh6KD/view?usp=share_link)

