packages used : 

django
python-dotenv 
djangorestframework
pytest
pytest-django
django-mptt
drf-spectacular
coverage
pytest-coverage


Commands used : 


py -m venv venv                                                 ==> creating virutal environemtnt
python.exe -m pip install --upgrade pip                         ==> upgrading pip
pip install django                                              ==> install django 
python -m django  --version                                     ==> Django Version
django-admin startproject drfecommerce                          ==> Starting a new django project named drfecommerce
python .\manage.py runserver                                    ==> Running the django project
from django.core.management.utils import get_random_secret_key  ==> to import the method get_random_secret_key
pip freeze > requirements.txt                                   ==> it will copy all the dependencies (all the packages used for this project)
pip install requirements.txt                                    ==> install the requirements that have been taken .
pip install python-dotenv                                       ==> to install python-dotenv for declaring the environments
pip install djangorestframework                                 ==> To install django rest frame work
pip install pytest                                              ==> to install pytest 
pytest -h                                                       ==> help routine
pip install pytest-django                                       ==> to install pytest django 
python .\manage.py startapp drfecommerce\product                ==> start a new inside the folder drfecommerce\product 
python .\manage.py makemigrations                               ==> To create migrations for the the newly created models into the django 
python .\manage.py migrate                                      ==> To do the migrations for the data models created
python .\manage.py createsuperuser                              ==> This command is to create a superuser in the django
pip install drf-spectacular                                     ==> To install DRF spectacular
pip install coverage                                            ==> to install coverage package