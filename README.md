
<!-- README.md is generated from README.Rmd. Please edit that file -->

# R/`tmle3`

[![Travis-CI Build
Status](https://travis-ci.org/tlverse/tmle3.svg?branch=master)](https://travis-ci.org/tlverse/tmle3)
[![AppVeyor Build
Status](https://ci.appveyor.com/api/projects/status/github/tlverse/tmle3?branch=master&svg=true)](https://ci.appveyor.com/project/tlverse/tmle3)
[![Coverage
Status](https://img.shields.io/codecov/c/github/tlverse/tmle3/master.svg)](https://codecov.io/github/tlverse/tmle3?branch=master)
[![Project Status: WIP – Initial development is in progress, but there
has not yet been a stable, usable release suitable for the
public.](http://www.repostatus.org/badges/latest/wip.svg)](http://www.repostatus.org/#wip)
[![License: GPL
v3](https://img.shields.io/badge/License-GPL%20v3-blue.svg)](http://www.gnu.org/licenses/gpl-3.0)

> The *Extensible* TMLE framework

**Author:** [Jeremy Coyle](https://github.com/jeremyrcoyle)

-----

## What’s `tmle3`?

`tmle3` is a general framework that supports the implementation of a
range of Targeted Maximum Likelihood / Minimum Loss-Based Estimation
(TMLE) parameters through exposing a unified interface. The goal is that
the `tmle3` framework be as general as the mathematical framework upon
which it’s based.

For a general discussion of the framework of targeted minimum loss-based
estimation and the role this methodology plays in statistical and causal
inference, the canonical references are van der Laan and Rose (2011) and
van der Laan and Rose (2018).

-----

## Installation

You can install the development version of `tmle3` from GitHub via
[`devtools`](https://www.rstudio.com/products/rpackages/devtools/) with

``` r
devtools::install_github("tlverse/tmle3")
```

-----

## Getting Started

The best place to get started is the “Framework Overview” document,
which describes the individual components of the `tmle3` framework. It
may be found here: <https://tmle3.tlverse.org/articles/framework.html>.

-----

## Issues

If you encounter any bugs or have any specific feature requests, please
[file an issue](https://github.com/tlverse/tmle3/issues).

-----

## License

© 2017-2018 [Jeremy R. Coyle](https://github.com/jeremyrcoyle)

The contents of this repository are distributed under the GPL-3 license.
See file `LICENSE` for details.

-----

## References

<div id="refs" class="references">

<div id="ref-vdl2011targeted">

van der Laan, Mark J, and Sherri Rose. 2011. *Targeted Learning: Causal
Inference for Observational and Experimental Data*. Springer Science &
Business Media.

</div>

<div id="ref-vdl2018targeted">

———. 2018. *Targeted Learning in Data Science: Causal Inference for
Complex Longitudinal Studies*. Springer Science & Business Media.

</div>

</div>