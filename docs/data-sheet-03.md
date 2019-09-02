# Data Sheet #3

* Figure 1

```python

    my_iterator = iter ( chickenjokes.generator() )

    print ( next ( my_iterator ) )

```

>An __iterator__ is an object that contains a countable number of values. An iterator can be __iterated__ upon, meaning that you can traverse through all the values.

>___Lists___, ___tuples___, ___dictionaries___, and ___sets___ are all __iterable__ objects. They are __iterable__ containers which you can get an __iterator__ from. All these objects have a _iter()_ method which is used to get an __iterator__:
