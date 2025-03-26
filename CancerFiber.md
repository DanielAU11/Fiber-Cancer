CancerFiber
================

How does dietary fiber intake relate to cancer risk? This document
explores the relationship between dietary fiber and cancer risk using
the `nutriR` and `Rcan` packages in R.

### Hypotheses

$H_0: \text {There is no significant relationship between dietary fiber intake and cancer risk.}$
$H_a: \text {There is a significant relationship between dietary fiber intake and cancer risk.}$

``` r
fiber_usa_data <- get_dists(nutrients = "Fiber", isos = "USA", sexes = "MF", ages = 18:80)
plot_dists(fiber_usa_data)
```

![](CancerFiber_files/figure-gfm/unnamed-chunk-2-1.png)<!-- -->
