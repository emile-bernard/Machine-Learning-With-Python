# Common bugs

## Description

Here is a list of common bugs and there solution.

## UnicodeDecodeError: 'charmap' codec can't decode byte X in position Y: character maps to <undefined>

Specify the encoding when you open the file:
```
file = open(filename, encoding="utf8")
```

## Can't Import Matplotlib.pyplot

```
pip uninstall matplotlib
python -m pip install --upgrade pip
pip install matplotlib
```

## Links

- [UnicodeDecodeError: 'charmap' codec can't decode byte X in position Y: character maps to <undefined>](https://stackoverflow.com/questions/9233027/unicodedecodeerror-charmap-codec-cant-decode-byte-x-in-position-y-character)

- [Can't Import Matplotlib.pyplot](https://github.com/matplotlib/matplotlib/issues/10252)
