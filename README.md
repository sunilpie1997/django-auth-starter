    ### Django Auth Starter ###

    Credits:https://simpleisbetterthancomplex.com/tutorial/2016/10/24/how-to-add-social-login-to-django.html
    
    ->  This is a django project with full featured accounts app that 
        can be used as template for your next django project.

    ->  You can add your own styles and customizations and use it as a starter template.

    Instructions

    ->  install django and all the requirements listed in requirements.txt.
    
    ->  install postgresql if not installed.

    ->  create database of your choice and edit 'DATABASE'
        property in 'settings.py' file

    ->  create google OAuth credentials from developer console 
        https://console.developers.google.com/apis/credentials?project=enduring-plate-283318

        REDIRECT URI SHOULD BE: 'http://localhost:8000/oauth/complete/google-oauth2/

    ->  add Google key and secret created from above process in 'google_conf.py' file

    ->  execute:

        ->  python manage.py makemigrations
        ->  python manage.py migrate
        ->  python manage.py runserver