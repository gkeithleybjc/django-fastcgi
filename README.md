Django FastCGI
--------------

I took the FastCGI written by some developers who understand it a lot better than I do, and packaged it into a pip installable package.

All credit to original authors of the fcgi command:  Allan Saddi, Ruslan Keba, Antoine Martin

To install:

`pip install django-fastcgi`

Then add 'django_fastcgi' to your INSTALLED_APPS.

Now you can use the manage.py command:

`python manage.py run_fcgi`


Why would I want to use this?
--------------

Well, I used it to deploy a Django application on IIS.  You can use it for whatever you like.
