

## Tools
#### Language
	Python (3.12.3)

### Back-end
	Django ==> 5.2.7

### Front-end
	Bootstrap ==> 5.1.3
	HTML-5
	CSS-3

#### Other libraries / tools:
	asgiref==3.4.1
	django-active-link==0.1.8
	django-crispy-forms==1.13.0
	django-flatpickr==1.0.1
	django-tinymce==3.4.0
	django-widget-tweaks==1.4.9
	Pillow==8.4.0
	pytz==2021.3
	sqlparse==0.4.2
	whitenoise==5.3.0
### Database
	PostgreSQL

## Base
	Every page includes navebar & footer.

Create a virtual environment to install dependencies in and activate it:
$ cd projet3
$ source projet3env/bin/activate
```
Then install the dependencies:
(projet3env)$ pip install -r requirements.txt
```
Once `pip` has finished downloading the dependencies:
(projet3env)$ python manage.py migrate
(projet3env)$ python manage.py runserver
```


