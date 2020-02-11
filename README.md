# Url-Shortener-Flask
A simple project disigned to shorten long url to 3 characters long.

## Required Packages
### Install Flask Package
* Type following command in CWD
    * pip install Flask
    * pip install pip install python-dotenv


## Running
* Set up the Database in CWD
   * from url_shortener import create_app
   * from url_shortener.extensions import db
   * from url_shortener.models import Link
   * db.create_all(app=create_app())


Just type the follewing command in the terminal in CWD.
* flask run
