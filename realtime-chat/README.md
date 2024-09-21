
#### Getting the files
Download zip file 

## Setup

#### - Create Virtual Environment
#####

python3 -m venv venv
source venv/bin/activate


###### # Windows

pip install virtualenv 
virtualenv venv 
venv\Scripts\activate.bat 
or
.\venv\Scripts\Activate.ps1

<br>

#### - Install dependencies

pip install --upgrade pip
pip install -r requirements.txt


<br>

#### - Migrate to database

python manage.py migrate
python manage.py createsuperuser(optional)


<br>

#### - Run application

python manage.py runserver


<br>



