# Data Sheet #2

## We can use the following to handle a spotify __Dataset__

* Figure 1

```python
    from src.spotify import Service

    search = Service("search")

    #returns compilation data
    data = search.get("compilation")

    print (data)
```

* Figure 2

```python
    #returns album data
    data = search.get("albums")

    #returns singles data
    data = search.get("singles")

```

* Figure 3

```python

    from src.myutility import add_media

    add_media("https://docs.python.org/3/_static/py.png", "Python:", "Famous familiar logo")

```
