# Hello

+++ 

_blue monday_

```python
from flask import Flask

app = Flask(__name__)

@app.route('/')
def hello_world():
    return 'Hello, World!'
```

@[1](import dependencies)
@[3](initiate the app with the name of the module)
@[5](set the route to respond on)
@[7-8](repond with the funciton `hello_world`)

---

# Goodbye

+++

**cruel world**
