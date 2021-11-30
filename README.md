# How To Use This Django Repository:
$ git clone https://github.com/VinCoD/learning_logs.git <br/>
$ cd learning_logs <br/>
$ virtualenv ll_env <br/>
$ source ll_env/bin/activate <br/>
$ pip install django <br/>
$ touch secret_settings.py <br/>

# in the secret_settings folder, add the following code:

SECRET_KEY = 'your_django_security key'<br/>
DEBUG = True<br/>
ALLOWED_HOSTS = []


# Note:
- Security Key can be found under settings.py of another django project, i can't share that here.
- If you don't know how to find one:
- create a new django project of your own, and in the settings.py you will find SECRET_KEY, copy the code and paste it under secret settings.py

# Regards
