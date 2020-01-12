# Blogsley-Django

## Requirements
PostgreSQL

        sudo apt update
        sudo apt install postgresql postgresql-contrib libpq-dev
## Installation

1. Navigate to a directory somewhere where you keep your software projects:

        cd projects

2. Clone the repository:

        git clone https://github.com/blogsley/blogsley-django.git
        
3. Navigate to the new directory which contains the repository.

        cd blogsley-django

4. Create a Python 3 virtual environment called `env`:

        python3 -m venv env
        
5. Activate the environment:

        source env/bin/activate
        
6. Install required packages:

        pip install -r requirements.txt


## Upgrading
        pip install -r requirements.txt
        ./manage.py makemigrations
        ./manage.py migrate

## Running the website

1. Activate the virtual environment, if not already active:

        cd blogsley-django
        source env/bin/activate
        
2. Start the Django web server:

        $ ./dev