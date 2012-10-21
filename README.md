Pocket
======

A python wrapper for the [pocket api](http://getpocket.com/api/docs).

Installation
------------
```
pip install pocket
```

Usage
------

First, you'll need your pocket api key. You can find this from your account page.
Then, you need to create an instance of the pocket object

```python
import pocket

pocket_instance = pocket.Pocket(username, password, api_key)
```

For detailed documentation of the methods available, please visit the official [pocket api documentation](http://getpocket.com/api/docs).
