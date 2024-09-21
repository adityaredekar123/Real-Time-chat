# Real-Time-chat


#### Getting the files
Download zip file 

## Setup

#### - Create Virtual Environment
#####

python3 -m venv venv <br>
source venv/bin/activate


###### # Windows

pip install virtualenv <br>
virtualenv venv <br>
venv\Scripts\activate.bat <br>
or<br>
.\venv\Scripts\Activate.ps1

<br>

#### - Install dependencies

pip install --upgrade pip<br>
pip install -r requirements.txt<br>



#### - Migrate to database

python manage.py migrate<br>
python manage.py createsuperuser(optional)<br>


<br>

#### - Run application

python manage.py runserver


<br>



