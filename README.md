### RDLOCRAND

The rdlocrand package provides Stata and R implementations of statistical inference and graphical procedures for Regression Discontinuity designs employing local randomization methods. It provides point estimators, confidence intervals estimators, binomial manipulation testing, windows selectors, automatic plots, sensitivity analysis, and other related features.

This work was supported in part by the National Science Foundation through grants [SES-1357561](https://www.nsf.gov/awardsearch/showAward?AWD_ID=1357561).


## Stata Implementation

To install/update in Stata type:
```
net install rdlocrand, from(https://raw.githubusercontent.com/rdpackages/rdlocrand/master/stata) replace
```

- Help: [rdrandinf](stata/rdrandinf.pdf), [rdwinselect](stata/rdwinselect.pdf), [rdsensitivity](stata/rdsensitivity.pdf), [rdrbounds](stata/rdrbounds.pdf).

- Replication: [do-file](stata/rdlocrand_illustration.do), [senate data](stata/rdlocrand_senate.dta).

## R Implementation

To install/update in R type:
```
install.packages('rdlocrand')
```

- Help: [R Manual](https://cran.r-project.org/web/packages/rdlocrand/rdlocrand.pdf), [CRAN repository](https://cran.r-project.org/package=rdlocrand).

- Replication: [R-script](R/rdlocrand_illustration.R), [senate data](R/rdlocrand_senate.csv). [R illustration](R/rdlocrand_illustration.pdf).

## References

For overviews and introductions, see [rdpackages website]().

### Software and Implementation

Cattaneo, Frandsen and Titiunik (2015): Randomization Inference in the Regression Discontinuity Design: An Application to Party Advantages in the U.S. Senate, Journal of Causal Inference 3(1): 1-24.
Cattaneo, Titiunik and Vazquez-Bare (2016): Inference in Regression Discontinuity Designs under Local Randomization, Stata Journal 16(2): 331-367.
Cattaneo, Titiunik and Vazquez-Bare (2017): Comparing Inference Approaches for RD Designs: A Reexamination of the Effect of Head Start on Child Mortality, Journal of Policy Analysis and Management 36(3): 643-681. [Replication Files]

### Technical and Methodological

- Cattaneo, Frandsen and Titiunik (2015): [Randomization Inference in the Regression Discontinuity Design: An Application to Party Advantages in the U.S. Senate](references/), Journal of Causal Inference 3(1): 1-24.

- Cattaneo, Titiunik and Vazquez-Bare (2017): Comparing Inference Approaches for RD Designs: A Reexamination of the Effect of Head Start on Child Mortality, Journal of Policy Analysis and Management 36(3): 643-681. [Replication Files]

<br>
<br>


