# Alphacare-assignment
This is the assignment solution.

To run the project Download and extract the Alphacare.zip file and follow the steps.

It contains core and frontend folder.

Django-Backend (core):

1. Create a virtual environment using the command ---->
    python -m venv venv
    
2. Now install the dependencies for the project using requirements.txt file --->
    pip install -r requirements.txt
    
3. Setup the project and make initial migrations --->
    python manage.py makemigrations
    python manage.py migrate
    
4. Create a Superuser --->
    python manage.py createsuperuser
    
5. Finally run the server --->
    python manage.py runserver
    

React Js (Front-end):
1. use npx-create-reactapp command to create a react project
2. All the dependencies and required packages are mentioned in package.json file.
3. Once all the dependencies are installed run the application using --->
    "npm start"
It will start the server at port 3000.
****make sure the react app will run in localhost:3000 as its allowed by the django cors origin (core-->settings.py)
