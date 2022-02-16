## Django-start
###### ! After cloning this repo and before running the necessary migration you have to add custom user model.

###### This is a Django starter project, you can clone or download zip and start your own project.
 
### 1. If you are cloning this repo change the github repo url:
```$ git remote set-url origin <new_repo_url_here_in_https_or_ssh>```
### Then you can check with:
```$ git remote -v```
### 2. Create your own postgres database (use pgAdmin e.g.)
### 3. Generte new secret-key for security reasons.
```$ python -c 'import secrets;print(secrets.token_urlsafe())'```
### 4. Create and fill env file witho your own data
```export DEBUG=True```
```export SECRET_KEY=<your_generated_secret_key_here>```
### 5. Install python packages in requirements file
```$ pipenv install -r requirements.txt```
### Then run virtual environment!
```$ pipenv shell```
### Test your job:
```$ python manage.py runserver```
###### If you can see the homepage after running localhost on your browser then you can use your new django app and you can deploying that later (to heroku e.g.)
###### You can make migrations and migrate now.
###### WARNING: If you would like to add customuser model to your django app you have to do it even before make migrations!


