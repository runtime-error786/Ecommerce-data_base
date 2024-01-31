DBProject
I've used Oracle 19c for the database as it was the requirement of our project. You'll need to install Oracle 19c on your machine before you can run it. Dont't forget to modify the DATABASES dictionary (username, password etc) declared in the settings.py file accordingly. The SQL code to create the schema and other database stuff is in extras>inventory.sql Make sure to run the SQL code from the inventory.sql file before you run the project.
Setup:
git clone https://github.com/your-username/folder_name.git
Install Python: Django is a Python web framework, so you need to have Python installed on your system. You can download and install Python from the official Python website. Make sure to install Python 3.x as Django is compatible with Python 3.

Install Django: Once you have Python installed, you can install Django using pip, Python's package manager. Open a terminal or command prompt and run the following command:
pip install django
Create a Django Project: After installing Django, you can create a new Django project using the django-admin command-line tool. Navigate to the directory where you want to create your project and run:
django-admin startproject projectname
django-admin startproject projectname
eplace projectname with the name of your project.

Create a Django App: Inside your Django project, you can create one or more apps. Apps are components of your project that handle specific functionality. Navigate into your project directory and run:
python manage.py startapp appname
Replace appname with the name of your app.

Configure Settings: Django settings are located in the settings.py file within your project directory. Configure database settings, static files, templates, middleware, etc., as needed for your project.

Run Migrations: Django uses migrations to manage database schema changes. Run the following command to apply migrations and create database tables:
![image](https://github.com/runtime-error786/Ecommerce-data_base/assets/123109871/be7f7d91-073b-4135-bf93-462672a23210)
![image](https://github.com/runtime-error786/Ecommerce-data_base/assets/123109871/0be5b8ce-a588-425f-b31f-21f46569b187)
![image](https://github.com/runtime-error786/Ecommerce-data_base/assets/123109871/507c5441-2a1f-44b2-bbbf-fa7948ccf7c5)
![image](https://github.com/runtime-error786/Ecommerce-data_base/assets/123109871/5e7883d4-82db-47cb-9923-e760e02d2179)
![image](https://github.com/runtime-error786/Ecommerce-data_base/assets/123109871/01698324-6d3c-41aa-888d-d6cdeb359c89)
![image](https://github.com/runtime-error786/Ecommerce-data_base/assets/123109871/d28b4a80-3cf9-499d-b17c-79413d941e6c)
![image](https://github.com/runtime-error786/Ecommerce-data_base/assets/123109871/e02ad311-981c-4fd8-a00a-3c9f06df732d)
