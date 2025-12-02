# An online store written on Django
### What can you do?
Add new product or category, add your product to cart, edit quantity of products

### Launch Guide
Copy this in your repository `git copy https://github.com/mrDisa/django-base.git`

Install this packages:
* asgiref==3.10.0
* Django==5.2.7
* pillow==12.0.0
* sqlparse==0.5.3
* tzdata==2025.2

Apply migrations `python manage.py migrate`

Run server `python manage.py runserver`

### How to add Product or Category?
* Create admin user `python manage.py createsuperuser`
* Run server `python manage.py runserver`
* Add admin to the address bar on your local server `http://127.0.0.1:8000/admin`
* Log into your admin user
* Add Product or Catedory
