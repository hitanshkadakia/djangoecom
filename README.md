Install the Requirements: pip install -r requirements.txt

Then, make database migrations: python manage.py makemigrations

python manage.py migrate

And finally, after a successful migration run the application: python manage.py runserver

At last, open up your favorite web browser

Go to URL “http://127.0.0.1/[ PORT_NUMBER ]/“

For the Admin Login credentials, you have to create one with a superuser.
