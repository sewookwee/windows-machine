# windows-machine

This document is to log the steps in configuring a Windows machine to setup AI/ML development environment

### Terminal - Windows Terminal
Install `Windows Terminal` from [Microsoft Store - Windows Terminal](https://apps.microsoft.com/detail/9N0DX20HK701).

## Development Environment
### Python

Install `Python 3.10` from [Microsoft Store - Python 3.10](https://www.microsoft.com/store/productId/9PJPW5LDXLZ5)

> **Note**: As of today (1/4/2024) some AI packages are not working well with Python 3.11 yet.

### Package Installer - [pip](https://pypi.org/project/pip/)

`pip` comes with above python installation. You want to upgrade it to the latest version. 
```
python -m pip install --upgrade pip
```

### Package Environment Manager - virtualenv
```
pip install virtualenv
```

### Virtual Environment & Install Packages
```
python -m virtualenv machine_learning
./machine_learning/Scripts/activate
pip install -r requirements.txt
```

