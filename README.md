https://flask.palletsprojects.com/en/2.1.x/tutorial/

To get it running:
```
$env:FLASK_APP = "flaskr"
$env:FLASK_ENV = "development"
flask run
```

After making setup.py and MANIFEST.in 
you can make  
pip install -e .  
This tells pip to find setup.py in the current directory and install it in editable or development mode

With:
in app.py in root folder:
from flaskr import create_app

if __name__ == '__main__':
    create_app()

we can do flask run without changing env