# pylua

[![Build Status](https://travis-ci.org/malirod/pylua.svg?branch=master)](https://travis-ci.org/malirod/pylua)

Example of binding between python and lua

## Platform

Ubuntu 18.10

## Prerequisite

- python 3 (3.6.7)

`sudo apt install python3-dev python3-pip python3-venv`

- lua 5.3

`sudo apt install liblua5.3 liblua5.3-dev`

## Setup

All further steps are performed in the project root

Create virtual environment

```bash
python3 -m venv venv
source venv/bin/activate
pip3 install --upgrade pip
pip install wheel
pip install -r requirements.txt
```

Install git hooks

`python ./tools/install_hooks.py`

## Usage

To run all tests run

`pytest`

## Code validation

Style check is performed with script `./tools/checkstyle.sh`