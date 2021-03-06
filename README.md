# python-cptv

This is Python package provides for quick, easy parsing for Cacophony
Project Thermal Video (CPTV) files. It works with **Python 3** only.

See [read.py](https://github.com/TheCacophonyProject/python-cptv/blob/master/read.py)
for example usage.

For more details on the internals of CPTV files, see the specifications:

* [version 1](https://github.com/TheCacophonyProject/go-cptv/blob/master/SPECv1.md).
* [version 2](https://github.com/TheCacophonyProject/go-cptv/blob/master/SPECv2.md).

## Installation

Installation from PyPI:

```
pip install cptv
```

Installation from source (use of a virtualenv is highly recommended):

```
pip install .
```

## License

This software is licensed under the Apache License 2.0.

## Releases

* Update the version in setup.py and commit.
* Ensure a Python 3 virtualenv is active.
* Build the source distribution: `python setup.py sdist --formats=zip`
* Tag the release, for example: `git tag -a v0.2.1 -m "0.2.1 release"`
* Push the tag to Github, for example: `git push origin v0.2.1`
* Push the release to PyPI, for example: `twine upload dist/cptv-0.2.1.zip`
