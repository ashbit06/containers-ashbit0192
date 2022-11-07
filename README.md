# Containers

Containers are a set of tuples, where each tuple contains the
name of the item and the amount of the item.

Initializing the Container should look like this:
```py
cont = Container(('jugs', 62), ('eggs', 11), ...)
```

or this:

```py
cont = Container()
cont.setItem('jugs', 62)
cont.setItem('eggs', 11)
...
```

## About

You might say I reinvented the dictionary, but no.
Containers are for storing amounts of items, and dictionaries
are for mapping values to keys. Technically that is what I
have done, but the value that gets mapped to the key is the
*amount* of that key. So no, this is not a dictionary.

Reccomended use for inventories in games.
