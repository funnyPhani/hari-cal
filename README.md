# Basic python package

```python
"""
Steps to install PyPI package
--------------------------------
python setup.py bdist_wheel
pip install -e .
python setup.py sdist
python setup.py bdist_wheel sdist
twine upload dist/*
"""
```


```python

pip install -U hari-cal

```

```python
from hari_cal import cal
cal()

```
