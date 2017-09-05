# ABCESL

[![DOI](https://zenodo.org/badge/95235014.svg)](https://zenodo.org/badge/latestdoi/95235014)


This is a python port of the entirety of
https://github.com/EconomicSL/distilledESL, further trimmed to its essence.
It is a plugin to [ABCE](https://github.com/AB-CE/abce);
`ABCESL` is a reference implementation of Economic
Simulation Library. I anticipate that the spec for the EconomicSL library will
be cross-language, just like in the case of a spec of an IETF RFC.

Currently it has a feature and implementation parity with:
https://github.com/EconomicSL/distilledESL/commit/1ef2d0a9fed490990f2a600b2916391de50bdea8 (May 10 2017)

The goal of this repo is to become a catalyst for a convergent evolution between the
API designs distilled-ESL / ABCE. Ideas can be tested much more
easily here.

While the ABCESL is currently used in Oxford for our stress testing model,
it is sparsely documented and lacks behavioral and unit tests. This is in
sharp contrast to ABCE, which has a good documentation and a test coverage
of all essential functions.

## Installation

This library uses Python >=3.5 type system, so it runs only on python>=3.5.

To install, run
```
$ pip install git+https://github.com/AB-CE/ABCESL.git
```

or from this repo
```
$ pip install .
```
