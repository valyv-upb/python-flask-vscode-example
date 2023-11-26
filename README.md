# python-flask-vscode-example
Based on https://code.visualstudio.com/docs/python/tutorial-flask 

# First steps
* Go to a desired location on your computer.
* Clone this repo as folder python-flask-vsode-example in current folder:
git clone  https://github.com/valyv-upb/python-flask-vscode-example.git

* Go into the folder:
cd python-flask-vscode-example

* Create the environment:

```python -m venv .venv```

* Activate the venv 
  * on Linux/MacOS

  ```source .venv/bin/activate```

  * on Windows
    
  ```.venv\Scripts\activate```

* Install flask
  
```pip install flask```

* Created a simple application called app.py with the code 

```from flask import Flask
app = Flask(__name__)

@app.route("/")
def home():
    return "Hello, Flask!"
```

* Then ran it with

```python -m flask run```
