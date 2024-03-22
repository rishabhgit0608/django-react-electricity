## Setup Instructions

### Creating and running the virtual environment. Needs python3

Create:

    virtualenv venv -p python3 or
    python3 -m virtualenv venv
    (For windows: `py -3 -m venv .`)

Run:

    source venv/bin/activate

    (For windows: `Scripts\activate`)

### Installing dependencies and running the server

`pip install -r requirements.txt`

`python manage.py migrate`

`python manage.py createsuperuser`

**Provide superuser credentials**

`python manage.py runserver`

## Formatting

1. pip install `black` in virtual env or local python
2. install `Microsoft's python extension` in vscode
3. search for `python formatting provider` in vscode settings and select `black`
4. enable `Format on Save`
