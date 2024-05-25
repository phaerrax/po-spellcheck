# po-spellcheck

Wrapper around `aspell` that adds basic support for `.po` files (requires [babel](https://pypi.python.org/pypi/Babel)).

```
usage: po-spellcheck [-h] -l LANG [-b] file [file ...]

positional arguments:
  file                  PO files to check for spelling errors

options:
  -h, --help            show this help message and exit
  -l LANG, --lang LANG  the target language of the PO file
  -b, --backup          if changes are made, create a .bak copy of the
                        original
```
