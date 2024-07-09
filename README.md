# Online Banking System

This is an Online Banking Concept created using Django Web Framework.


## Features

* Create Bank Account.
* Deposit & Withdraw Money
* Bank Account Type Support (e.g. Current Account, Savings Account)
* Interest calculation depending on the Bank Account type
* Transaction report with a date range filter 
* See balance after every transaction in the Transaction Report
* Calculate Monthly Interest Using Celery Scheduled tasks
* More efficient and accurate interest calculation and balance update
* Ability to add Minimum and Maximum Transaction amount restriction
* Modern UI with Tailwind CSS


## Prerequisites

Be sure you have the following installed on your development machine:

+ Python >= 3.7 (must be)(better create a virtual environment)
+ Redis Server
+ Git
+ pip
+ Virtualenv (virtualenvwrapper is recommended)

## Requirements

+ celery==4.4.7
+ Django==3.2
+ importlib-metadata==4.13.0
+ django-celery-beat==2.0.0
+ python-dateutil==2.8.1
+ redis==3.5.3

## Project Installation

To setup a local development environment:

Create a virtual environment in which to install Python pip packages. With [virtualenv](https://pypi.python.org/pypi/virtualenv),
```bash
python -m venv .venv            # create a virtualenv # or manually create a virtualenv
.\.venv\Scripts\activate   # activate the Python virtualenv 
```

Clone GitHub Project,
```bash
git@github.com:MSSohan/Online-Banking-System.git

cd banking-system
```

Install development dependencies,
```bash
pip install -r requirements.txt
```

Migrate Database,
```bash
python manage.py migrate
```

Run the web application locally,
```bash
python manage.py runserver # 127.0.0.1:8000
```

## More Help [Projectworlds](https://projectworlds.in/online-banking-system-project-in-python-django/)
