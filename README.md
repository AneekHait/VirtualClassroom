


                      VIRTUAL CLASSROOM   

It is a college project for a Virtual Classroom base on Django Framework.

INSTALLING INSTRUCTION:

    Pre-requisits: Python3, git

Clone this repository

  -> git clone https://github.com/AneekHait/VirtualClassroom.git

Change to VirtualClassroom directory

  -> cd VirtualClassroom

Create a Virtual Environment

  ->  python -m venv venv

Activating Virtual Environment

    for Windows
        -> cd venv\Scripts
        -> activate.bat
        
    for Linux    
        -> source venv/bin/activate

Downloading Dependencies

  ->  pip install -r requirements.txt

Migrating Database ( Default:- sqlite3 )

  ->  python manage.py makemigrations
  ->  python manage.py migrate        

Create Superuser / Admin account

  ->  python manage.py createsuperuser

Finally, to run project

  ->  python manage.py runserver

We are working hard to fix existing bugs and implementing new features. You are also welcome to contribute towards this project.
Thank You.
