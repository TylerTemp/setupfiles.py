<!--
README generated with readmemako.py (github.com/russianidiot/readme-mako.py) and .README dotfiles (github.com/russianidiot-dotfiles/.README)
-->

## About this fork ##

I don't know what this is, but the original one doesn't work on
python 3.5.2 and breaks one of my package dependence.

This fork can run and only tested on python 3.5.2

Install:

```bash
pip install git+https://github.com/TylerTemp/setupfiles.py.git
```

---------

![python](https://img.shields.io/badge/language-python-blue.svg)
[![PyPI](https://img.shields.io/pypi/pyversions/setupfiles.svg)](https://pypi.python.org/pypi/setupfiles)[![PyPI](https://img.shields.io/pypi/v/setupfiles.svg)](https://pypi.python.org/pypi/setupfiles)

[![codacy.com](https://api.codacy.com/project/badge/Grade/a4e30fd25a0546449f20e544dc70cfc4)](https://www.codacy.com/app/russianidiot-github/setupfiles-py/dashboard)
[![landscape.io](https://landscape.io/github/russianidiot/setupfiles.py/master/landscape.svg?style=flat)](https://landscape.io/github/russianidiot/setupfiles.py)
[![codeclimate.com](https://codeclimate.com/github/russianidiot/setupfiles.py/badges/gpa.svg)](https://codeclimate.com/github/russianidiot/setupfiles.py)
[![scrutinizer-ci.com](https://scrutinizer-ci.com/g/russianidiot/setupfiles.py/badges/quality-score.png?b=master)](https://scrutinizer-ci.com/g/russianidiot/setupfiles.py/)

[![drone.io](https://drone.io/github.com/russianidiot/setupfiles.py/status.png)](https://drone.io/github.com/russianidiot/setupfiles.py)
[![scrutinizer-ci.com](https://scrutinizer-ci.com/g/russianidiot/setupfiles.py/badges/build.png?b=master)](https://scrutinizer-ci.com/g/russianidiot/setupfiles.py/)
[![semaphoreci.com](https://semaphoreci.com/api/v1/russianidiot/setupfiles-py/branches/master/shields_badge.svg)](https://semaphoreci.com/russianidiot/setupfiles-py)
[![shippable.com](https://api.shippable.com/projects/57a8ea795aa7620d0090f095/badge?branch=master)](https://app.shippable.com/projects/57a8ea795aa7620d0090f095/status/)
[![travis-ci.org](https://api.travis-ci.org/russianidiot/setupfiles.py.svg)](https://travis-ci.org/russianidiot/setupfiles.py)
[![wercker.com](https://app.wercker.com/status/91a89abae3dce961ed671d94f4d9de65/s/master)](https://app.wercker.com/#applications/57a8fd55c248330100ad2c7a)

<p align="center">
    <b>distutils/setuptools replacement</b>
</p>

#### Install

`[sudo] pip install setupfiles`

#### Features
*	**native** - based on distutils/setuptools
*	**setup() auto arguments** - **files** or **environment variables**

#### Usage

```python
>>> from setupfiles import setup
```

#### Environment variables
*	$NAME, $DESCRIPTION, $KEYWORDS, $LONG_DESCRIPTION, $VERSION, $DEPENDENCY_LINKS, $ENTRY_POINTS, $INSTALL_REQUIRES

```
export VARIABLE="$VARIABLE"
```

#### Example

```bash
# default (auto keys)
>>> setup()

# define arguments
>>> setup(name="pkgname",version="0.4.2")
```

[Examples/](https://github.com/russianidiot/setupfiles.py/tree/master/Examples)

#### Structure
```
path/to/repo
└───bin
│   │   script1
│   │   script2
│
└───py_modules
│   │   modname1.py
│   │   modname2.py
│
└───packages
│   └───pkgname1
│       └───data
│       │   │   any_file.png
│       │   │   any_file.txt
│       │
│       │   __init__.py
│       │   filename.py
│
│ 	dependency_links.txt
│ 	description.txt
│ 	entry_points.txt
│ 	keywords.txt
│ 	requirements.txt
│ 	version.txt
```

Feedback
[![GitHub issues](https://img.shields.io/github/issues/russianidiot/setupfiles.py.svg)](https://github.com/russianidiot/setupfiles.py/issues)
[![Join the chat at https://gitter.im/russianidiot/setupfiles.py](https://badges.gitter.im/russianidiot/setupfiles.py.svg)](https://gitter.im/russianidiot/setupfiles.py)
[![GitHub followers](https://img.shields.io/github/followers/russianidiot.svg?style=social&label=Follow)](https://github.com/russianidiot)

* * *

<p align="center">
	Python packages <a href="http://russianidiot.github.io/python/">russianidiot.github.io/python/</a>
	<img src="http://russianidiot.github.io/images/python/16.png" />
</p>
<p align="center">
	cli packages <a href="http://russianidiot.github.io/cli/">russianidiot.github.io/cli/</a>
<img src="http://russianidiot.github.io/images/cli/16.png" />
</p>

<p align="center">
	repos list <a href="http://russianidiot.github.io/">russianidiot.github.io</a> <img src="http://russianidiot.github.io/images/star/16.png" />
</p>
