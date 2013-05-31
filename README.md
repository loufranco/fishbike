fishbike
=========
Pure Procedural Programming

_A woman needs a man like a fish needs a bicycle_ -- Irina Dunn

fbc is a self-hosted, combination interpreter and compiler for the fishbike language. Fishbike programs are run like this:

```fbc program.fb```

Or, you can compile them like this

```fbc program.fb > program```

and run that like this (after chmod +x)

``` ./program ```

fbc is self-hosted, so

```fbc fbc > fbc2```

Results in fbc2, which is an fishbike interpreter/compiler.

Here is a program to find all primes not divisible by themselves

```shell
touch primes.fb
fbc primes.fb
```

Enjoy!
