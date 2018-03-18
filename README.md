# openscad-unit

Unit tests for [OpenSCAD](http://www.openscad.org/) libraries

* [Installation](#installation)
* [Examples](#examples)
* [Questions/Support](#questionssupport)

[![Build Status](https://travis-ci.org/little-blossom/openscad-unit.svg?branch=master)](https://travis-ci.org/little-blossom/openscad-unit)

## Installation

* Clone this repository.
* Make sure you have a recent [OpenSCAD](http://www.openscad.org/) installed (`2015.03-1` will do)
* Running `test` from your clone will look for and run tests in `*.scad` files underneath the current directory.

## Examples

To see `openscad-unit` in action, check out [`openscad-qbase`](https://github.com/little-blossom/openscad-qbase). Simply clone `openscad-qbase`, and run the `test` script. This will extract the tests from the `*.scad` files, render the tests to `test-results` and compare them to the provided `test-expectations`.

## Questions/Support

If you run into issues or have questions, please file a ticket at [GitHub](https://github.com/little-blossom/openscad-unit/issues/new)
