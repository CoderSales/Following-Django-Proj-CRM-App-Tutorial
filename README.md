# Following-Django-Proj-CRM-App-Tutorial

Following a Django Tutorial to Build a CRM App Tutorial

## Steps

- conda deactivate base
- [install virtual environment](https://youtu.be/t10QcFx7d5k?t=197)
- [activate virtual environment](https://youtu.be/t10QcFx7d5k?t=211)
- [pip install django](https://youtu.be/t10QcFx7d5k?t=223)
- python.exe -m pip install --upgrade pip
- [pip install mysql](https://youtu.be/t10QcFx7d5k?t=230)
- [Download mysql](https://youtu.be/t10QcFx7d5k?t=234)
- [connector from Django to mysql app](https://youtu.be/t10QcFx7d5k?t=241)

  - [There are 2 connectors](https://youtu.be/t10QcFx7d5k?t=245)

    - [pip install mysql-connector](https://youtu.be/t10QcFx7d5k?t=246)
    - [pip install mysql-connector-python](https://youtu.be/t10QcFx7d5k?t=253)

- [download and install mysql](https://youtu.be/t10QcFx7d5k?t=274)
- [dev.mysql.com](https://dev.mysql.com/)

  - [dev.mysql.com/downloads/installer/](https://dev.mysql.com/downloads/installer/)
  - MySQL Installer 8.0.34

- [Community installer](https://youtu.be/t10QcFx7d5k?t=288)
- [link 2 of 2 with the ~300M file size](https://youtu.be/t10QcFx7d5k?t=290)
- [click download](https://youtu.be/t10QcFx7d5k?t=293)

## Installation Note

- [Important: setup Username and Password](https://youtu.be/t10QcFx7d5k?t=304)

## Turn on MySQL Server

- [Turn on MySQL Server](https://youtu.be/t10QcFx7d5k?t=330)

  - [MySQL needs to be running in the background](https://youtu.be/t10QcFx7d5k?t=337)

- [head back over to terminal](https://youtu.be/t10QcFx7d5k?t=343)

- [django-admin startproject dcrm](https://youtu.be/t10QcFx7d5k?t=352)

- [setup git](https://youtu.be/t10QcFx7d5k?t=818)

- [See code pushed to GitHub remote repository](https://youtu.be/t10QcFx7d5k?t=997)

- [First webpage working](https://youtu.be/t10QcFx7d5k?t=1289)

- [In base.html is the code that will go on every page](https://youtu.be/t10QcFx7d5k?t=1306)

- [Bootstrap](https://youtu.be/t10QcFx7d5k?t=1309)

- [getbootstrap.com](https://youtu.be/t10QcFx7d5k?t=1314)

- [Docs](https://youtu.be/t10QcFx7d5k?t=1319)

- [change light to dark navbar](https://youtu.be/t10QcFx7d5k?t=1547)

- [navbar has been tidied up](https://youtu.be/t10QcFx7d5k?t=1688)

____________________

- [Django login users](https://youtu.be/t10QcFx7d5k?t=1728)

- [views.py import authenticate log in out and messages](https://youtu.be/t10QcFx7d5k?t=1790)

- [how request works](https://youtu.be/t10QcFx7d5k?t=1847)

- [url](https://youtu.be/t10QcFx7d5k?t=1871)

- [Form added with baasic modification](https://youtu.be/t10QcFx7d5k?t=2155)

- [Cut log me out tick box](https://youtu.be/t10QcFx7d5k?t=2174)

- [Username and Password formatted](https://youtu.be/t10QcFx7d5k?t=2251)

- [Login button clicking should do nothing (Fixed earlier error, see README/Bugs/Issue:Login...)](https://youtu.be/t10QcFx7d5k?t=2261)

- [Username and Password need to be requireed](https://youtu.be/t10QcFx7d5k?t=2266)

- [There was an error login Bootstrap message with x working](https://youtu.be/t10QcFx7d5k?t=2836)

- [Login and Logout working](https://youtu.be/t10QcFx7d5k?t=3037)

- [Register Users](https://youtu.be/t10QcFx7d5k?t=3106)

- [Register Page exists](https://youtu.be/t10QcFx7d5k?t=3282)

- [Registration updated, tutorial commit](https://youtu.be/t10QcFx7d5k?t=3868)

  GitHub for Tutorial:
  - [tutorial 'registration' commit](https://github.com/flatplanet/Django-CRM/commit/b7b5d76f88963010ac93e897a67416a5243c74f0)

  - [relevant code: form.py](https://github.com/flatplanet/Django-CRM/blob/main/website/forms.py)

- [Add registration detail - Done](https://youtu.be/t10QcFx7d5k?t=4433)

- [end setting up site | start crm](https://youtu.be/t10QcFx7d5k?t=4483)

- [Django DataBase Model](https://youtu.be/t10QcFx7d5k?t=4503)

- [Python/Django creates a class that abstracts away and creates code for us on the backend.](https://youtu.be/t10QcFx7d5k?t=4530)

  - [It will create the MySQL code if you're using MySQL](https://youtu.be/t10QcFx7d5k?t=4537)

  - [It will create the PostgreSQL code](https://youtu.be/t10QcFx7d5k?t=4540)

  - [Whatever DataBase you're using, it will do it for you behind the scenes.](https://youtu.be/t10QcFx7d5k?t=4542)

- [define class](https://youtu.be/t10QcFx7d5k?t=4548)

- [In models.py Add class Record and Define subelements](https://youtu.be/t10QcFx7d5k?t=4758)

- [Record model migration applied](https://youtu.be/t10QcFx7d5k?t=4991)

- [Records model added to admin.py](https://youtu.be/t10QcFx7d5k?t=5061)

## Bugs

Issue: Login button goes to a 403 page with CSRF missing
Cause: form element missing closing triangular bracket in templates/home.html
Fix: add closing triangular bracket to form element

## References

- [Tutorial](https://youtu.be/t10QcFx7d5k?t=139)
