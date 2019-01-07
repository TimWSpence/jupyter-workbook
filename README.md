Jupyter Workbook
=======================

A template project to setup a Jupyter workbook with the requisite dependencies installed,
including [Coconut](http://coconut-lang.org/), which sucks a bit less than Python.

Setup
------

```bash
python3 -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt
coconut --jupyter notebook
```

Installed packages
---------------------

* coconut
* pandas
* scipy
