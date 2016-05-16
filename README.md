# flask_example
This is a very simple Flask app that demonstrates what is needed to deploy a working Flask application to Heroku, using gunicorn.
- Gunicorn is installed - check requirements.txt.
- The Procfile tells Heroku to launch the app using gunicorn.
- "runtime.txt" tells Heroku what version of Python to use - in this case, 3.5.1.

Check it out at https://flask-example-app.herokuapp.com/
