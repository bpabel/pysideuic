pysideuic
=========

Provides PySide dynamic .ui file loading similar to the PyQt uic functionality.


Installation
------------

```sh
pip install git+https://github.com/bpabel/pysideuic.git
```

Usage
-----

The `loadUi()` function takes a path to .ui file and an object to load it onto.

```python
from pysideuic import loadUi

class MyWidget(QWidget):

    def __init__(self, *args, **kwargs):
        super(MyWidget, self).__init__(*args, **kwargs)
        loadUi('mywidget.ui', self)

```


