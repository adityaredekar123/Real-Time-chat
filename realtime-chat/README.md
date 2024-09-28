# Real-Time-chat



#### Getting the files
Download zip file or <br>
Clone with git 

<br><br><br>

## Setup

#### - Create Virtual Environment
###### # Mac
```
python3 -m venv venv
source venv/bin/activate
```

###### # Windows
```
pip install virtualenv 
virtualenv venv 
.\venv\Scripts\activate 
```

<br>

#### - Install dependencies
```
pip install --upgrade pip
pip install -r requirements.txt
```

<br>

#### - Migrate to database
```
python manage.py makemigrations
python manage.py migrate
python manage.py createsuperuser(admin)
```

<br>

#### - Run application
```
python manage.py runserver
```

<br>


