# FlaskWebApp
Web app using python's flask

## Create virtual enviroment using python virtualenv
``` $ virtualenv flaskapp ```
## Open virual enviroment
``` $ source flaskapp/bin/activate ```
## Create database
### First go to /src folder
``` $ cd /src ```
### Open python
``` $ python ```
### Create database
``` > from FlaskBlogApp import db ```

``` > db.create_all() ```
## Start server 
### Start Server
``` $ python run.py ```
## Enjoy from your browser
Running on http://127.0.0.1:5000/
