===================
quantized-mesh-tile
===================

[![Build Status](https://travis-ci.org/loicgasser/quantized-mesh-tile.svg?branch=master)](https://travis-ci.org/loicgasser/quantized-mesh-tile)
[![Coverage Status] (https://coveralls.io/repos/github/loicgasser/quantized-mesh-tile/badge.svg?branch=master)](https://coveralls.io/github/loicgasser/quantized-mesh-tile?branch=master)

Quantized-mesh-tile is a Python encoder/decoder and topology builder for terrain tiles.

## Styling

Max line length is 90.

We use flake8 to lint the project. Here are the rules we ignore.

- E128: continuation line under-indented for visual indent
- E221: multiple spaces before operator
- E241: multiple spaces after ':'
- E251: multiple spaces around keyword/parameter equals
- E272: multiple spaces before keyword
- E711: comparison to None should be 'if cond is None:' (SQLAlchemy's filter syntax requires this ignore!)
- E731: do not assign a lambda expression, use a def
- W503: line break before binary operator