# meta-backend-capstone

Steps to run the app<br>
1. Install pipenv<br>
pip install pipenv<br>

2. Create a .env file in the root folder<br>
DATABASE = YOUR_MYSQL_DATABASE_NAME<br>
USER     = YOUR_USERNAME             # default is root<br>
PASSWORD = YOUR_MYSQL_PASSWORD<br>
HOST     = localhost                 # or 127.0.0.1<br>
PORT     = 3306<br>

3. Install dependencies <br>
pipenv install<br>

4. Make migrations <br>
py manage.py makemigrations<br>

5. Migrate <br>
py manage.py migrate<br>

6. Run the app <br>
py manage.py runserver<br>

To run tests <br>
py manage.py test tests<br>
