# pycounts_am

Counting words in a text file.

## Installation

```bash
$ pip install pycounts_am
```

## Usage

### Imports
```python
from pycounts_am.pycounts_am import count_words
from pycounts_am.plotting import plot_words
```

### Count Words
```python
count_words("pycounts_am/zen.txt")
```

### Plot Words
```python
word_counts = count_words("pycounts_am/zen.txt")
plot_words(word_counts, n=5)
```

## Contributing

Interested in contributing? Check out the contributing guidelines. Please note that this project is released with a Code of Conduct. By contributing to this project, you agree to abide by its terms.

## License

`pycounts_am` was created by adammorphy. It is licensed under the terms of the MIT license.

## Credits

`pycounts_am` was created with [`cookiecutter`](https://cookiecutter.readthedocs.io/en/latest/) and the `py-pkgs-cookiecutter` [template](https://github.com/py-pkgs/py-pkgs-cookiecutter).
