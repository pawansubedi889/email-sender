This is a simple send-email application built using django.


To use this application, simply clone the repo, then, 

create .env file with the following details:
EMAIL_HOST_USER = #sender's email-id
EMAIL_HOST_PASSWORD = #password associated with above email-id generated from manage google account settings (not the regular password)


and run the application with:
python manage.py runserver
