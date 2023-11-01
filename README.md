# django-medium-registration

pip install djangorestframework
pip install djangorestframework-simplejwt

register:
http://127.0.0.1:8000/account/api/register/
body:
{
  "email": "",
  "name" : "",
  "password": ""
}


login:
http://127.0.0.1:8000/account/api/login/
body:
{
  "email" : "",
  "password" : ""
}


