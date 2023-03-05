# meta-backend-capstone

Steps to run the app<br>
1. Install pipenv<br>
pip install pipenv

2. Create a .env file in the root folder<br>
DATABASE = YOUR_MYSQL_DATABASE_NAME
USER     = YOUR_USERNAME             # default is root
PASSWORD = YOUR_MYSQL_PASSWORD
HOST     = localhost                 # or 127.0.0.1
PORT     = 3306

3. Install dependencies <br>
pipenv install

4. Make migrations <br>
py manage.py makemigrations

5. Migrate <br>
py manage.py migrate

6. Run the app <br>
py manage.py runserver

To run tests <br>
py manage.py test tests
