## Django-start
##### * This is a Django starter project, you can clone or download zip and start your own project.

#### 1. If you are cloning this repo change the github repo url:
```$ git remote set-url origin <new_repo_url_here_in_https_or_ssh>```
##### Then you can check
```$ git remote -v```
#### 2. Create your own postgres database (use pgAdmin e.g.)
#### 3. Generate new secret-key for security reasons.
```$ python -c 'import secrets;print(secrets.token_urlsafe())'```
#### 4. Create env file with your own data
```export DEBUG=True```
```export SECRET_KEY=<your_generated_secret_key_here>```
#### 5. Install the python packages
```$ pipenv install -r requirements.txt```
#### Then run virtual environment
```$ pipenv shell```
#### Test your job
```$ python manage.py runserver```
##### * If you can see the homepage after running localhost on your browser then you can use your new django app and you can deploying that later (to heroku e.g.)
##### * You can make migrations and migrate now.
##### WARNING: If you would like to add custom user model to your django app you have to do it even before make migrations!


