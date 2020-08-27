**Backend REST API with python & django - advanced**
By Mark Winterbottom
admin@site.com
incognito

-Create a dir to hold the project codes & cd into it.
-cmd "pipenv install" to create a virtualenv for this project.
-cmd "pipenv shell" to activate the virtualenv
-cmd "pipenv install django==2.2 djangorestframework" to install django v.2.2 & djangorestframework
-cmd "django-admin startproject app ." to create a django project called app within the dir
-cmd "python manage.py startapp app_core" to create app called app_core. Next register the app in settings.py file under "INSTALLED_APPS" dict.
-Create custom User model to use email instead of username inside "models.py" file then add
"AUTH_USER_MODEL = 'appName.User'" inside "settings.py" file
-cmd "python manage.py makemigrations appName"

**Section 14**

