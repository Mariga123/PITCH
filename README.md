### Application Name
* Pitch

## Author
* Mariga

### Description
* A project for users to add their pitches,comment on other peoples pitches, edit profile and create bio.
* This will help Users practice on different types of pitches under calculated time,and be professionals during pitch presentation.

### Application Overview
* Home page Overview
*   <img src="static/photos/home.png">

* Account Overview
*   <img src="static/photos/account.png">

## To run my page on your browser,

* Git  clone https://github.com/Mariga123/PITCH.git to your terminal
* Open the pitch with your text editor.
* Install necessary requirements as highlighted on [run](**pip install -r requirements.txt**)

### creating a DATABASE
*   1.Go to your terminal Install postgress bt [run](sudo apt-get install postgresql postgresql-contrib libpq-dev)
*   2. Open your shell by using **psql**
*   3. Create database by *CREATE DATABASE pitchy;*
*   4. Connect to your database by */c pitchy*
*   5.To view your database structure use *select *from Users;*

* ##### Exporting database configurations
* export SQLALCHEMY_DATABASE_URI=postgresql+psycopg2://{User Name}:{password}@localhost/{database name}

* Use pip install with the version of your text editor
* To render the page live locally, run **Python3 manage.py run**

## Known Bugs
* Still editing on mail search authentification for signup template.

## Technologies Used
* Python3.7
* flask
* Heroku

## Support and contact details
* email *johnmariga8@gmail.com*
* phn: *0742249975*
* fb *zellyjones*
* instagram *Mariga john*

### License
licensed under [MIT license](LICENSE)