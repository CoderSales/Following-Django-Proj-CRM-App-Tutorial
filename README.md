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

- [Start of 'Django View Records on Website' timestamp on tutorial](https://youtu.be/t10QcFx7d5k?t=5150)

- [Return record at front end | View but still not formatted correctly](https://youtu.be/t10QcFx7d5k?t=5462)

- [Start of Django Bootstrap Table for formatting | Same timestamp twice for different topics | (Purpose of 2 timestamps is to delineate different topics)](https://youtu.be/t10QcFx7d5k?t=5462)

- [Table added to site](https://youtu.be/t10QcFx7d5k?t=5726)

- [Prepare for adding extra formatting from Bootstrap Table Docs](https://youtu.be/t10QcFx7d5k?t=5726)

- [table-hover class added to table in home.html](https://youtu.be/t10QcFx7d5k?t=5770)

- 1:36:41 [Border added to table](https://youtu.be/t10QcFx7d5k?t=5801)

- 1:36:57 [table-sm | table small class](https://youtu.be/t10QcFx7d5k?t=5817)

- 1:37:14 [Cut table-sm | table small class](https://youtu.be/t10QcFx7d5k?t=5834)

- 1:37:34 [Add table-dark class (to `<thead>` element) | Purpose: To make table header row dark](https://youtu.be/t10QcFx7d5k?t=5854)

- 1:37:55 [Identify TODO items and Plan next steps](https://youtu.be/t10QcFx7d5k?t=5875)

- 1:38:25 [Next Step: Django Individual Records](https://youtu.be/t10QcFx7d5k?t=5905)

- 1:43:57 [Added customer records page accessible only when logged in | Access page by primary key by passing (`/<int:pk>`) | setup url in urls.py, view in views.py and record.html in templates folder](https://youtu.be/t10QcFx7d5k?t=6237)

- 1:45:10 [Hovering over record ID links on page causes bottom left corner of site to display (hosted site home page)/record/(id#)](https://youtu.be/t10QcFx7d5k?t=6310)

- 1:45:38 [TODO Add content to record/<int:pk>](https://youtu.be/t10QcFx7d5k?t=6338)

- 1:46:14 [Added customer record to record page](https://youtu.be/t10QcFx7d5k?t=6374)

- 1:48:43 [Added content to records page | TODO: Add Bootstrap Card (formatting)](https://youtu.be/t10QcFx7d5k?t=6523)

- 1:56:52 [Added Bootstrap Card and Buttons (unconnected) to records page | TODO: Delete Record](https://youtu.be/t10QcFx7d5k?t=7012)

- 2:01:07 [Wired up Delete Record Button on record page | TODO: Add "Add Records" Functionality](https://youtu.be/t10QcFx7d5k?t=7267)

- 2:03:09 [Add "Add Record" button to navbar](https://youtu.be/t10QcFx7d5k?t=7389)

- 2:12:12 [Added 'Add Record' Form to 'Add Record' Page | TODO: Update Records](https://youtu.be/t10QcFx7d5k?t=7932)

## Bugs

Bug Number: 1

Issue: Login button goes to a 403 page with CSRF missing

Cause: form element missing closing triangular bracket in templates/home.html

Fix: add closing triangular bracket to form element

______________________________________________________________________________________________;

Bug Number: 2

Context:

  File: forms.py

  Line Number: 40

  Line Content: first_name = Forms.CharField(required=True, widget=forms.widgets.TextInput(attrs={"placeholder":"First Name", "class":"form-control"}), label="")

  Issue: First letter capitalization of Forms

  Fix: Change Forms to forms

## References

- [Tutorial](https://youtu.be/t10QcFx7d5k?t=139)
- [ChatGPT3.5](https://chat.openai.com/?model=text-davinci-002-render-sha)
- [VisualStudioCode]
- [Sublime]

### VSCode Extensions

- [Live Server | Go Live]
- [Copilot]
- [Tabnine AI Autocomplete for Javascript, Python, Typescript, PHP, Go, Java, Ruby & more]
- [GitLens]
- [IntelliCode]
- [IntelliCode API Usage Examples]
- [Pylance]
- [Python]
- [Python Environment Manager]
- [Python Extension Pack]
- [WSL]
- [Path Intellisense]
- [Live Preview]
- [isort]

### Packages

- [Django]
- [Bootstrap]

### DataBase

- [MySQL]
- [mysql-connector]
- [mysql-connector-python]
- [mysqlclient]
