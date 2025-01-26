# Pre-requisites:

> The following programs are required to run the project

- [Any Python-3 version](https://www.python.org/downloads/)
- [PostgreSQL database](https://www.postgresql.org/download/)

# Installation

- Clone the repo with `git clone https://github.com/ShadowBOB12345/IUCA-Startapp-Okututor.git`

- Create and activate a python virtual environment

- `pip install -r requirements.txt`

- Create `.env` file inside the root directory and include the following variables
```config
DB_NAME=[YOUR_DB_NAME]
DB_USER=[DB_ADMIN_NAME]
DB_PASSWORD=[DB_PASSWORD]
DB_HOST=localhost
DB_PORT=
USER_EMAIL=[YOUR_EMAIL]
USER_PASSWORD=[EMAIL_PASSWORD]
STRIPE_SECRET_KEY=LEAVE_THIS_BLANK_FOR_NOW
STRIPE_PUBLISHABLE_KEY=LEAVE_THIS_BLANK_FOR_NOW
```

- `python manage.py makemigrations`

- `python manage.py migrate`

- `python manage.py runserver`

Last but not least, go to this address http://127.0.0.1:8000

