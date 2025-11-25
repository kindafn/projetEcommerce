

## Tools
#### Language
	Python (3.10)

### Back-end
	Django ==> 3.2.8

### Front-end
	Bootstrap ==> 5.1.3
	Fontawesome ==> 4.7.0
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
	Sqlite

## Base
	Every page includes navebar & footer.



Create a virtual environment to install dependencies in and activate it:
```sh
$ cd projet3
$ source projet3env/bin/activate
```
Then install the dependencies:
```sh
(projet3env)$ pip install -r requirements.txt
```

Once `pip` has finished downloading the dependencies:
```sh
(projet3env)$ python manage.py migrate
(projet3env)$ python manage.py runserver
```

## Home page
Home page shows product category & products. It has a paginations of 12 products.
!![home page]

## Single product view
After clicking the product image, it will show the product’s descriptions.

![Single product view]


## Category-wise view
After clicking catery title, products of these category will be shown.
![Category-wise view]

## Cart Page
![Cart Page]

## Checkout Page
![Checkout Page]

## Order History
![Order History]

## Search Page
![Search Page]

## Acount Page (Login, Sign up & Update)
###  Login page
![Login]

###  Sign up
![Sign up]

###  Acount Update page
![Update]	

# Admin Page
## Admin Dashboard
![Admin Dashboard]

## Admin-Order Dashboard
![Admin-Order Dashboard]

### Total Order List
![Total Order List]

### Pending Order List
![Pending Order List]

### Processing Order List
![Processing Order List]

### Shipped Order List
![Shipped Order List]

### Delivered Order List
![Delivered Order List]

## Customer-List
![Customer-List]

## Product-Dashboard
![Product-Dashboard]

## Update Status
![Update Status]

## Admin-Category Dashboard
![Admin-Category Dashboard]

### Category update view
![Category update view]

### Category List
![Category List]

The End


