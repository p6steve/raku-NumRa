Here is to thrash out requirements. Please also reference / link sources.

### architecture

- looks like Python Numpy is built [mostly in C](https://stackoverflow.com/questions/1825857/how-much-of-numpy-and-scipy-is-in-c)
- there are many library options - https://en.wikipedia.org/wiki/List_of_numerical_libraries

### direction

- build this module mostly in C for performance (assume that C is ubiquitous on Raku installs)
- use one of the FOSS licensed C libraries via Raku [nativecall](https://docs.raku.org/language/nativecall)

### steps

- review NumPy features vs. C lib features
