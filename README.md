# Mavins Lee: Deadly Simple Haskell Scotty Tutorial

This is the source code for a
[tutorial](https://lucchesi.com.br/api-rest-em-haskell-usando-o-scotty/)
I wrote on my blog (in PT-BR).

## Building and running

Make sure you have [Stack](https://docs.haskellstack.org/en/stable/README/)
installed and run:

```bash
$ git clone https://github.com/alexandrelucchesi/haskell-scotty-tutorial.git
$ cd haskell-scotty-tutorial
$ stack build
$ stack exec -- mavins-lee
```

Optionally, instead of running `build` and `exec`, you can load the application
into GHCi with `stack ghci` and call `main` from there. This is particurlaly
useful during development.
