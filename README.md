# PyUnitX

[![PyPI Version](https://img.shields.io/pypi/v/pyunitx.svg)](https://pypi.org/project/pyunitx/)

[![License](https://img.shields.io/pypi/l/pyunitx.svg)](https://github.com/fullstack-spiderman/pyunitx/blob/main/LICENSE)

[![Python Versions](https://img.shields.io/pypi/pyversions/pyunitx.svg)](https://pypi.org/project/pyunitx/)

[![Coverage Status](https://coveralls.io/repos/github/fullstack-spiderman/pyunitx/badge.svg?branch=main)](https://coveralls.io/github/fullstack-spiderman/pyunitx?branch=main)

A custom unittest runner for Python's unittest framework.

## Features

- Custom test result reporting.
- Colorful and informative test status output.
- Support for Python 3.8 and above.

## Installation

You can install PyUnitX using pip:

```bash
pip install pyunitx
```

## Usage

Run your tests using PyUnitX by simply invoking the pyunitx command.
For example:

```bash
pyunitx discover -s tests -p "test_*.py" -v
```

You can pass the following arguments to the pyunitx command:

```bash
-s or --start-directory: Specify the directory to start test discovery (default is '.').
-p or --pattern: Specify the test file pattern (default is 'test*.py').
-v or --verbosity: Specify the verbosity level (default is 1).
For more options and details, use the pyunitx --help command.
```

## Contributing

Contributions are always welcome!
Feel free to open issues, submit pull requests, or provide feedback.

## License

[MIT](https://choosealicense.com/licenses/mit/)
