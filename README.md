[![PyPi](https://img.shields.io/pypi/v/xlsx2html.svg)](https://pypi.python.org/pypi/xlsx2html)
[![Build Status](https://travis-ci.org/Apkawa/xlsx2html.svg?branch=master)](https://travis-ci.org/Apkawa/xlsx2html)
[![Codecov](https://codecov.io/gh/Apkawa/xlsx2html/branch/master/graph/badge.svg)](https://codecov.io/gh/Apkawa/xlsx2html)
[![Requirements Status](https://requires.io/github/Apkawa/xlsx2html/requirements.svg?branch=master)](https://requires.io/github/Apkawa/xlsx2html/requirements/?branch=master)
[![PyUP](https://pyup.io/repos/github/Apkawa/xlsx2html/shield.svg)](https://pyup.io/repos/github/Apkawa/xlsx2html)
[![Python versions](https://img.shields.io/pypi/pyversions/xlsx2html.svg)]()
[![License](https://img.shields.io/badge/license-MIT-blue.svg)](LICENSE)

# xlsx2html

A simple export from xlsx format to html tables with keep cell formatting


# Install

```bash
pip install xlsx2html
```


# Usage

```python
from xlsx2html import xlsx2html

xlsx2html('path/to/example.xlsx', 'path/to/output.html')
```


# Contributors
```bash
pip install -r requirements.txt
pytest # run tests
tox # run test matrix
```

## publish
```bash
python setup.py sdist upload -r pypi
```