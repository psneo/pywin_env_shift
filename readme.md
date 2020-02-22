# pywin_env_shift

## Introduction
A simple python package to help you shift python setup, to make binary in Scripts folder (e.g. pip)workable despite different python exe path.

## How to use
1) Install this to the python environment you want to shift
2) run
```python -m pywin_env_shift.main --pack``` to pack zip python environment into a zipfile.
3) Locate the zipfile at current working directory
4) copy to another host, unzip and run ```python -m pywin_env_shift.main --convert```
5) all the exe in Scripts folder will be usuable