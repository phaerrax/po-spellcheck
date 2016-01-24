## spellcheck

Wrapper around `aspell` that adds basic support for `.po` files (requires `babel`).

```
usage: spellcheck [-h] [-b] lang file [file ...]

positional arguments:
  lang
  file

optional arguments:
  -h, --help    show this help message and exit
  -b, --backup  if changes are made, create a .bak copy of the original
```
