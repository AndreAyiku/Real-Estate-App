# Real-Estate-App
## Guide
### Run this command in Powershell to Set up the virtual environment

###  For MAC :
```bash
python -m venv venv
source venv/bin/activate 
pip install Flask Flask-SQLAlchemy psycopg2-binary Flask-WTF Flask-Login
```
### For Windows:
```bash
python -m venv venv
.\venv\Scripts\Activate
pip install Flask Flask-SQLAlchemy psycopg2-binary Flask-WTF Flask-Login
```
Now if you get a restricted access error, you have to open powershell as administrator and run these commands;
```bash
Get-ExecutionPolicy # To see your current restriction
Set-ExecutionPolicy -Scope Process -ExecutionPolicy Bypass # to bypass if it is restricted
```
#### Then re-run the codes above.
#### After activation, your prompt should change to show (venv) at the beginning.
#### Do not leave the powershell window 

## How to run the app

#### Okay, so now, in the same PowerShell window you have open, redirect the location of the app.py.
#### Run this:
```bash
pip install Flask psycopg2-binary
python app.py
```
#### You should see your server address provided
#### please note that this is all locally hosted and I'm yet to figure out how to make it public but the database connection works, it is similar to phpmyadmin
#### Also ive used html for the pages, dont worry we can change it to react or something else later, right now its just to test the flask app



