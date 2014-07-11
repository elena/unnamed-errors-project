

### Basic 'Not-Plugged-In' Errors

---

`AttributeError: 'NoneType' object has no attribute 'objects'`

FACTORY_FOR = myapp.MyModel

`myapp.Model` isn't found.

workarounds:

    from . import models
    ...
    FACTORY_FOR = models.MyModel

---