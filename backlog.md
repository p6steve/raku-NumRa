Here is to thrash out requirements. Please also reference / link sources.

### architecture

- looks like Python Numpy is built [mostly in C](https://stackoverflow.com/questions/1825857/how-much-of-numpy-and-scipy-is-in-c)
- there are many library options - https://en.wikipedia.org/wiki/List_of_numerical_libraries

### direction

- build this module mostly in C for performance (assume that C is ubiquitous on Raku installs)
- use one|more of the FOSS licensed C libraries via Raku [nativecall](https://docs.raku.org/language/nativecall)
- lean into [PerlPDL](https://en.wikipedia.org/wiki/Perl_Data_Language)

### discards

- not Java / JVM (yet)

### steps

- get PerlPDL working via inline::<Perl5>
- get Numpy working via inline:<Pythoh>
- get some common examples working (aka test v1)
- review NumPy features vs. C lib features
