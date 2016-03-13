# fullstack-nano-degree-p3


Project 3 Item/Category Catalog
================================

Creating a web application using flask, SQLite and OAuthentification

Requirements
------------
- Vagrant and VirtualBox Must be installed
- Clone the fullstack-nanodegree-vm to the desired directory
- Launch the Vagrant VM via the vagrant up command in the fullstack repository

Dependencies and supported Python versions
------------------------------------------
- Python version 2.7.*
- flask
- sqlalchemy
- database_setup.py
- oauth2client
- os

Creating The Database
----------------- 
In order to setup the database and populate the data, please run this commands:

    python database_setup.py if you choose
    python init_events.py

You are better off using the current database bundled with the application.

Test
------
Run the web server using:
```python
python application.py
```

Misc
-----
- Google oauth should work with no issues
- Facebook works for the given user account with andrewsyc@yahoo.com but no other at the moment
- Some items are left listed as event as refactoring didn't work well when switching goals of this project up. eventlist.db would be better off named restaurants.db
