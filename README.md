# py_summarize_it

A package to summarize information of a text file

## Installation

```bash
$ pip install py_summarize_it
```

## Usage

`py_summarize_it` can be used to count words in a text file and plot results
as follows:

```python
from py_summarize_it.py_summarize_it import count_words
from py_summarize_it.plotting import plot_words
import matplotlib.pyplot as plt

file_path = "test.txt"  # path to your file
counts = count_words(file_path)
fig = plot_words(counts, n=10)
plt.show()
```

## Contributing

Interested in contributing? Check out the contributing guidelines. Please note that this project is released with a Code of Conduct. By contributing to this project, you agree to abide by its terms.

## License

`py_summarize_it` was created by Sopuruchi Chisom. It is licensed under the terms of the MIT license.

## Credits

`py_summarize_it` was created with [`cookiecutter`](https://cookiecutter.readthedocs.io/en/latest/) and the `py-pkgs-cookiecutter` [template](https://github.com/py-pkgs/py-pkgs-cookiecutter).
