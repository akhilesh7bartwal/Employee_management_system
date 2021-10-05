# Employee Management System with implementing CRUD-Operations
Complete Django CRUD Operations with PostgreSQL

 # How it works ?
 In order to work with Postgres from the Django project i installed psycopg2.
installation command :  pip install psycopg2

Functionalities:
 - 1. Add employee information:
    * Full Name
    * Mobile
    * Employee code
    * Position

 - 2. Edit and Delete:
    * Be able to edit and delete employees from the database. An employee's details are automatically populated when the user clicks the edit button

 - 3. Display employees:
    * Be able to retrieve employees from a list button and display them

 - 4. Used technologies:
    * Bootstrap
    * html,css,js
    * python (Django)
    * postgreSQl

								: App Structure :

● employee_project
|
+---● employee_register (app folder)
|   |
|   +--● migrations (includes files related to migrations)
|   |  
|   +--● templates
|   |  |--● employee_register
|   |  |  |--base.html
|   |  |  |--employee_form.html
|   |  |  |--employee_list.html
|   |  |  |--home.html
|   |
|   |-- models.py
|   |-- forms.py
|   |-- urls.py
|   |-- views.py
|
|
+---● employee_project (project folder)
|   |
|   |--settings.py 
|   |--urls.py

	


