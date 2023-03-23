### To create the database:
From terminal run:
>>> `from app import app, db`
>>>`app.app_context().push()`
>>> `db.create_all()`
This will create the database in a folder called instance.