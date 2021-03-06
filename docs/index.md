# IEX-API-Python

![IEX-API-Python Logo](iex_logo.png)

[![Build Status](https://travis-ci.org/danielecook/iex-api-python.svg?branch=master)](https://travis-ci.org/danielecook/iex-api-python) [![Coverage Status](https://coveralls.io/repos/github/danielecook/iex-api-python/badge.svg)](https://coveralls.io/github/danielecook/iex-api-python) ![Python 3.6](https://img.shields.io/badge/Python-3.6-blue.svg)


### Summary

The `iex-api-python` module is a wrapper for the [IEX API](https://iextrading.com/developer/docs/#getting-started), and is designed to closely map to the organization of the original API while adding functionality. A few examples of the additional functionality are:

* Many queries are returned as [Pandas Dataframes](https://pandas.pydata.org/).
* Built-in support for websockets connections.
* Option to format timestamps as datetime objects or ISO format.

### Installation

* __Python >=3.6__

``` bash
pip install iex-api-python
```

### Getting Started

From the [API documenation](https://iextrading.com/developer/docs/#getting-started):

> The IEX API is a set of services designed for developers and engineers. It can be used to build high-quality apps and services. We’re always working to improve the IEX API. Please check back for enhancements and improvements.

* [Read the terms](https://iextrading.com/api-terms/).
* [Read the manual](https://iextrading.com/developer/docs/#market-data) and start building.
* [Attribute properly](https://iextrading.com/developer/docs/#attribution).

**The API terms apply to the use of this module, as does the requirement to properly attribute the use of IEX data.**
