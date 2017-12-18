[![Build Status](https://travis-ci.org/Bohdan-Khomtchouk/FTPflow.svg?branch=master)](https://travis-ci.org/Bohdan-Khomtchouk/FTPflow)
[![Open Source Love](https://badges.frapsoft.com/os/gpl/gpl.svg?v=102)](https://github.com/ellerbrock/open-source-badge/)
[![PyPI version](https://badge.fury.io/py/FTPflow.svg)](https://badge.fury.io/py/FTPflow)

# FTPflow

`FTPflow` is a Python package for optimally traversing extremely large FTP directory trees.  It constitutes the algorithmic heart of the [Airport](https://github.com/airportbio/airport-web) search engine.  FTPflow creates a dictionary formatted as a JSON file in the user’s home directory containing all the full paths as keys and the respective filenames as values.  FTPflow is designed with speed in mind by utilizing state-of-the-art high performance parallelism and concurrency algorithms to traverse FTP directory trees.  The resultant hash table (i.e., dictionary) supports fast lookup for any file in any biological database.

## Screenshots

<img width="496" alt="morpheus_walk" src="https://cloud.githubusercontent.com/assets/9893806/23974988/c4ec5264-09b4-11e7-8503-255ec7a04111.png">
