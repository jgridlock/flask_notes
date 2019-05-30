# Flask Notes
## Setup
Download Python3+ which comes with pip and venv.  
What venv does is create a virtual environment where packages can be installed that do not effect the global packages. This is done because if you have an application that works only on a lower version it will not be effected.  
Create a project folder and cd into it.  
Create a virtual env by running `python -m venv venv`  
From inside your project folder run venv\Scripts\activate to start the virtual environment. This has to be done from cmd prompt.  

Folder structure
project/
    venv/
    app/
        __init__.py
        routes.py
    projectname.py