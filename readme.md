# make-livescript
GNU Make include for [LiveScript](https://github.com/gkz/LiveScript).

## usage

```
npm install make-livescript
```

Then in your Makefile:
```makefile
include node_modules/make-livescript/livescript.mk
```

Then `make` compiles all `.ls` files nested under `src/` and puts the resulting `.js` files in `lib/`, and `make clean` removes `lib/`.

## config
```makefile
SRC = 'path/to/livescript/files'
LIB = 'path/to/output/dir'
LS_OPTS = 'pass flags to lsc'
```

## licence
[MIT](/licence.md)