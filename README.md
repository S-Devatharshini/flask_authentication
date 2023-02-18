# Installation steps

* Setup the virtual environment

    virtualenv -p python3 .venv

* Activate the virtual environment

    venv/Scripts/activate

* Install Flask,Flask-Login,Flask-SQLAlchemy

    python -m pip install flask

    python -m pip install flask-login

    python -m pip install flask-sqlalchemy

# Setting Up the database

* In the terminal,make use of the python shell

    from project import db, create_app, models
    db.create_all(app=create_app()) 

# Start the server

    flask run

**Note:The server runs on http://127.0.0.1:5000

# Demo video

[click here to view the demo](https://drive.google.com/file/d/1tguLipe6is9-Llv52hR-9_bPNOJUfBf6/view?usp=sharing)

