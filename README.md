# Test Streamlit

## Installation

Create a virtual environment

```bash
python<version> -m venv <env name>
```

Activate the virtual environment

```bash
source <env name>/bin/activate
```

To deactivate the virtual environment:

```bash
deactivate
```

Freeze requirements

```bash
pip freeze > requirements.txt
```

Install dependancies

```bash
pip install -r requirements.txt
```

## pip

### Updating Python Packages on Windows or Linux

List of all outdated packages:

```bash
pip list --outdated
```

Edit `requirements.txt`, and replace all "==" with ">=".

Update

```bash
pip install -r requirements.txt --upgrade
pip freeze > requirements.txt
```