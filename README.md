# Simple flask introduction App code-along

Installation:
- cd into root directory
- run `pipenv shell`
- then `pipenv install`
- then `pipenv run dev`

## To install virtualenv required for database management
- cd into root directory
- run `pip install virtualenv`
- run `virtualenv venv` (venv is the name, can use any name)

## Accessing the Python shell for database initialisation:
- cd into root directory
- in cmd and enter the command `.\venv\Scripts\activate` It will activate the virtual env in windows
- type `python` to enter the python environment
- type `from app import db`
- type `db.create_all()`
