Simple Markdown
===================

Simple markdown to HTML compiler. Used in BCC328 to review concepts of 
Haskell programming language.

Dependencies
-------------

The code was tested on GHC 9.6.1 and cabal 3.10.1. 

Running
--------

In order to build the
code, execute:

```
cabal new-build
```

This will compile and install all necessary dependencies. The REPL can be
started using

```
cabal new-repl
```

You can run the executable using

```
cabal new-run simple-markdown 
```


A help message on which arguments are expected by the compiler can be 
obtained by:

```
cabal new-run simple-markdown -- --help
```
