FLASK QUERIES

1. python -m pip install flask
2. set FLASK_APP = market.py  // application name
3. set FLASK_DEBUG = 1   // To ON debug mode
4. python -m pip install flask-sqlalchemy
5. python -m pip install email_validator
6. python -m pip install wtforms  // forms
7. python -m pip install flask_bcrypt  // to generate hash passwords
8. pip install flask_login




DATABASE QUERIES

1. from market(APP_NAME) import db
2. db.create_all()
3. from market import Item    (class where db is defined)
4. input data => item1 = Item(name = "IPhone 10" , price = 10000 , barcode = '123492837345", description = ' desc.' )
5. db.session.add(item1)  // item created
6. db.session.commit()  // saving information in database

7. Item.query.all()  // no. of input data added
8. for item in Item.query.all():
	item.name
	....etc
9. for item in Item.query.filter_by(price = 10000):
	item.name ... etc
10. import os
os.system('cls')
11.  item1 = Item.query.filter_by(name  = 'Iphone 10')
       item1 = Item.query.filter_by(name  = 'Iphone 10').first()
       item1
12. 






