# meta-backend-capstone

Steps to run the app
1. Install pipenv
pip install pipenv
2. Create a .env file in the root folder
# .env
DATABASE = YOUR_MYSQL_DATABASE_NAME
USER     = YOUR_USERNAME             # default is root
PASSWORD = YOUR_MYSQL_PASSWORD
HOST     = localhost                 # or 127.0.0.1
PORT     = 3306
3. Install dependencies
pipenv install
4. Make migrations
py manage.py makemigrations
5. Migrate
py manage.py migrate
6. Run the app
py manage.py runserver
To run tests
py manage.py test tests
