# API for social network Yatube

## Description

API for the social network of bloggers Yatube. The project is implemented on the DJANGO REST API.
  
#### Available functions

- JWT tokens are used for authentication.
- Unauthenticated users have read-only access to the API.
- An additional restriction has been set for the /follow/ endpoint. Only authenticated users can access it.
- Authenticated users are allowed to modify and delete their content, otherwise access is read-only.
- User subscriptions.
- View, create, edit and delete entries.
- View and create groups.
- Ability to add, edit, delete your comments and view others.
- Filtering by fields.

#### API documentation is available at [http://127.0.0.1:8000/redoc/](http://127.0.0.1:8000/redoc/) after "python manage.py runserver" 

#### Tech

- Python 3.7
- Django 2.2.16
- Django Rest Framework 3.12.4
- Djoser 
- Simple JWT
- SQLite3

#### Running a project in dev-mode

- Clone the repository:
``` git clone <repository name> ```
- Install and activate the virtual environment:
``` python -m venv venv ```
``` source venv/Scripts/activate ```
- Install dependencies from requirements.txt file:
``` pip install -r requirements.txt ```
- Go to api_yatube/yatube_api folder.
- Apply migrations:
``` python manage.py migrate ```
- Run the command:
``` python manage.py runserver ```

#### Full list of API requests are in the documentation

#### Author

Maksimov Kirill