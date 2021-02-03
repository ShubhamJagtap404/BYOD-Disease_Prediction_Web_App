### General Disease Prediction based on symptoms provided by patient- powered by Django & Machine Learning


# How To Use This
First make sure PostgreSQL and pgadmin is install in your system. 
then you have to manually create a DB instance on PostgreSQL named "byod", better use PgAdmin for that.
Also, after setting-up your own password for PostgreSQL server, add the same password in the setting.py file like here


![db password change](https://user-images.githubusercontent.com/51310448/106695579-e6043280-6600-11eb-894a-5bea7a5f67a3.jpg)


- Run pip install -r requirements.txt to install dependencies
- Run python manage.py makemigrations
- Run python manage.py migrate
- Run python manage.py runserver
- Navigate to http://127.0.0.1:8000/ in your browser


