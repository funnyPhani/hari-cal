# Basic python package

## to tets the package use the link

[GoogleColabLink](https://colab.research.google.com/drive/1eM-teLOPFBKA7-mDkVfQTobw_MaI8jNw?usp=sharing)

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
