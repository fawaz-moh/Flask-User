============
Installation
============

We recommend making use of virtualenv and virtualenvwrapper::

    mkvirtualenv my_env
    workon my_env

Installation Instructions
-------------------------

After setting up virtualenv, installation is as easy as::

    workon my_env
    pip install flask-user

Requirements
------------
- Python 2.7, 3.4 or 3.6
- Flask 0.12+
- Flask-Login 0.4+
- Flask-Mail 0.9+ or Flask-Sendmail
- Flask-WTF 0.14+
- passlib 1.6+
- pycrypto 3.1.1+
- pycryptodome 3.4.6+

When using the included SQLAlchemyAdapter, Flask-User requires:

- Flask-SQLAlchemy 2.2+ (with a driver such as MySQL-Python or PyMySQL)

Optional requirements for Event Notification:

- blinker 1.3+

Optional requirements for Internationalization:

- Flask-Babel 0.11.2+
- speaklater 1.3+

Up Next
-------
:doc:`basic_app`

