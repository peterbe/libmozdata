# libmozdata
> Library to access and agregate several Mozilla data sources

The goal is to provide a library giving access to a wide range of Mozilla data sources. This library also provides some post processing on data.


[![Build Status](https://api.travis-ci.org/mozilla/libmozdata.svg?branch=master)](https://travis-ci.org/mozilla/libmozdata)
[![codecov.io](https://img.shields.io/codecov/c/github/mozilla/libmozdata/master.svg)](https://codecov.io/github/mozilla/libmozdata?branch=master)

## Setup

Install the prerequisites via `pip`:
```sh
sudo pip install -r requirements.txt
```

## Running tests

Install test prerequisites via `pip`:
```sh
sudo pip install -r test-requirements.txt
```

Run tests:
```sh
coverage run --source=libmozdata -m unittest discover tests/
```

## Credentials

Copy the file config.ini-TEMPLATE into config.ini and fill the token entries.
