# Unofficial Tellonym SDK for Python
![GitHub Contributors](https://img.shields.io/github/contributors/logxn/tellonym-python.svg)
![GitHub Repo Size](https://img.shields.io/github/repo-size/logxn/tellonym-python.svg)
![GitHub License](https://img.shields.io/github/license/logxn/tellonym-python.svg)

A unofficial python module to easily interact with [Tellonym](https://tellonym.me)

## Usage
```python
from tellonym import Tellonym as tell

tell = tell.Tellonym(username, password)
```

### Tells
```python
>>> tell.delete_tell(tell_id)
```

### Misc
```python
>>> tell.logout()
```