# FlaskWebApp
Web app using python's flask

## First clone current repository
```
git clone https://github.com/al1998petridis/FlaskWebApp.git 
```

Go to cloned directory with 
```
cd FlaskWebApp/
```

## Create virtual enviroment using python virtualenv
```
virtualenv flaskapp
```

## Open virual enviroment
```
source flaskapp/bin/activate
```

## Install dependencies
```
pip install -r requirements.txt
```

## Create database
### First go to /src folder
```
cd /src
```
### Open python
```
python
```
### Create database
```
from FlaskBlogApp import db
```

```
db.create_all()
```

```exit()
```

## Start server 
### Start Server
```
python run.py
```
## Enjoy from your browser
Running on http://127.0.0.1:5000/
