# Install some useful pip files  

# for a postgresql database
pip install psycopg2

# for a mysql database
pip install mysqlclient #python3
pip install MySQL-python #python2

# for use on heroku
pip install gunicorn dj-database-url

# Create superuser and save database 
python manage.py migrate
python manage.py createsuperuser

# Install GIT and Heroku from offical websites 

# Create Git Ignore anf PROCFILE

# Create requirement.txt and runtime.txt
