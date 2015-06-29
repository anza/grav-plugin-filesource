
# Grav filesource plugin

`filesource` is a plugin which allows embedding file sources to a page as text.

Based on [Grav PageInject Plugin](https://github.com/getgrav/grav-plugin-page-inject)
by [rhukster](https://github.com/rhukster)


## TODO

* write better readme
* sanitize paths and reading files
* add options how to format the embedded file
  * templates, perhaps?


# Config defaults 

```
enabled: true
```


# Usage

`[plugin:filesource](*filename*)` where *filename* is name of the file (in the same directory as the post) to be embedded
