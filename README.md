# gdrive-datastore

A package that facilitates storing data to Google Drive

## build

To build distribution, simply run:

> python -m build

## install locally for testing

To install localling for testing, simply run:

> python -m pip install .

## test locally

To test locally, simply run:

> pytest tests

## upload to test pypi

To upload to test pypi, simply run:

> python -m twine upload --repository testpypi dist/*

## install from test pypi

To install from test pypi, simply run: 

> python -m pip install --index-url https://test.pypi.org/simple/ --no-deps gdrive-datastore
