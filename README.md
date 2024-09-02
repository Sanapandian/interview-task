OVERVIEW
 This project provides a simple RESTful API to perform CRUD operations.

REQUIREMENTS
- Python 3.8+
- Django 4.0+
- Django REST Framework 3.14+
- SQLite3 (default database)

STEPS 
Step-1
 clone the repository
 open the project in vscode

Step-2:setup a Django project
i)Create a virtual environment
  python -m venv myenv
ii)Execute by using 
  myenv/scripts/activate

Step-3 Apply migrations
  python manage.py migrate

Step-4 create superuser
  python manage.py createsuperuser

Step-5 Run development server
  python manage.py runserver

Step-6 To access API

  The API will be available at http://127.0.0.1:8000/myapp/books/. You can use the following endpoints:

List Books: GET /myapp/books/
Retrieve a Book: GET /myapp/books/{id}/
Create a Book: POST /myapp/books/
Update a Book: PUT /myapp/books/{id}/
Delete a Book: DELETE /myapp/books/{id}/
