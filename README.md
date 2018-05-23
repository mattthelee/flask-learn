# flask-learn
My first play around with flask following the tutorial here: https://blog.miguelgrinberg.com/post/the-flask-mega-tutorial-part-i-hello-world

#Prerequisites
```pip install flask flask-wtf flask-sqlalchemy flask-migrate flask-login flask-bootstrap```

# Running:
To run do the following:
```export FLASK_APP=myflask.py
flask run```

#Note to self:
I can set `export FLASK_DEBUG=1` to activate debug mode which puts more useful logs to the browser and allows browser based python terminal too! It will also reload the application anytime the source files are changed :) Careful not to run in prod systems.
