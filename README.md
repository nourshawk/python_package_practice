# python_package_practice

A toy package using the word count functions from py-pkgs template

## Installation

```bash
$ pip install python_package_practice
```

## Usage

`python_package_practice` can be used to count words in a text file and plot results
as follows:

```python
from python_package_practice.python_package_practice import count_words
from python_package_practice.plotting import plot_words
import matplotlib.pyplot as plt

file_path = "test.txt"  # path to your file
counts = count_words(file_path)
fig = plot_words(counts, n=10)
plt.show()
```

## Contributing

Interested in contributing? Check out the contributing guidelines. Please note that this project is released with a Code of Conduct. By contributing to this project, you agree to abide by its terms.

## License

`python_package_practice` was created by Nour Shawky. It is licensed under the terms of the MIT license.

## Credits

`python_package_practice` was created with [`cookiecutter`](https://cookiecutter.readthedocs.io/en/latest/) and the `py-pkgs-cookiecutter` [template](https://github.com/py-pkgs/py-pkgs-cookiecutter).
