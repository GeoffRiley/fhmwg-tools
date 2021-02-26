# fhmwg-tools

…or to put it another way "Family History Metadata Working Group" example metadata reading and writing tools.

The [Family History Metadata Working Group](https://fhmwg.org/) (FHMWG) has been working on a specification for keeping data of particular interest to family historians together with any graphic images that pertain to them. Current metadata tends not to be transported between different packages and platforms, neither is there any ready agreement over the exact purpose over the metatags that are in use.

Over the last year the FHMWG has examined the current state of metadata available and narrowed down a set of metatags that are fully defined and easily understood. The results are presented in the documentation at:

* [FHMWG Metadata Standards v1.0 (Technical Summary)](https://github.com/fhmwg/current-tags/blob/master/stage1-overview.md)
* [FHMWG Metadata Standards v1.0 (Full normative specification)](https://github.com/fhmwg/current-tags/blob/master/stage1.md)

This is a _recommended standard_, and it is hoped that it will become a vehicle to greatly aid the problem that exists of images and metadata being separated.

# Python implementation

The members of the FHMWG have already implemented [a C++ reference library](https://github.com/fhmwg/cpp-code), it is my intention to work on a similar implementation for Python.

## Requirements

Minimal requirements for working with graphics and metadata in general include:

* `PIL` / `pillow`
* `python-xmp-toolkit`
* `python` v3.7+
