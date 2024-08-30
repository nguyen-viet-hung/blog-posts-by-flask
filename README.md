# Flaskr - A sample of blueprint
This repo contains materials for building a backend that serves personal posts. It includes some techniques:
* Flask serves APIs.
* Flask - blueprint for modularize big project into sub modules.
* Jinja2 template for rendering resources based on specific templates.

This repo was taken from the [tutorial](https://flask.palletsprojects.com/en/2.3.x/tutorial/factory/) of Flask with modifications of blog's `index.html`. Use Javascript technique to display current local time instead of UTC of blog creation time.

Step for running your own blog:
* Install required packages
* Initialize database
* Execute the backend

## Install required packages
Here we can use virtual environment of Python module or conda environment. After you activate the environment, run following command to install required packages
```shell
$ pip install -r requirements.txt
```
## Initialize database
Before running backend, you must initialize its database using following command:
```shell
$ flask --app flaskr init-db
```
This command will create a schema that is used by backend

## Execute the backend
After initializing database, now we can run the backend using following command:
```shell
$ flask --app flaskr run --debug --host 0.0.0.0
```
Now you can open the link [http://127.0.0.1:5000](http://127.0.0.1:5000) and here you go.
