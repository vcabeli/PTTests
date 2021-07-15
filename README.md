# miic in Polya Tree independence tests (PTTests) benchmarks

This is a fork of the R package for the paper at UAI2021 by Philip A. Boeken and Joris M. Mooij

'A Bayesian Nonparametric Conditional Two-sample Test with an Application to Local Causal Discovery' (Boeken and Mooij, 2021)

With the miic (conditional) mutual information estimation and significance test added for comparison for JFRB (Journées Francophones sur les Réseaux Bayésiens) 2021. See 'output' folder for comparison benchmarks.

## Installation

To install this R package, make sure you have R (version >= 3.5.0) and RStudio installed. Open ``PTTests.Rproj`` in RStudio and execute:

```R
install.packages("devtools")
devtools::install_local("./")
library(PTTests)
```

For miic, visit https://github.com/miicTeam/miic_R_package/ or run :

```R
# install.packages("remotes")
remotes::install_github("miicTeam/miic_R_package")
```

Refer to the original repository for further information https://github.com/philipboeken/PTTests

## miic References
Cabeli V., Verny L., Sella N., Uguzzoni G., Verny M., Isambert H.; Learning clinical networks from medical records based on information estimates in mixed-type data; PLoS computational biology., 2020. [doi:10.1371/journal.pcbi.1007866](https://doi.org/10.1371/journal.pcbi.1007866) | [code](https://github.com/vcabeli/miic_PLoS)

Li H., Cabeli V., Sella N., Isambert H.; Constraint-based causal structure learning with consistent separating sets; [In Advances in Neural Information Processing Systems 2019.](https://papers.nips.cc/paper/9573-constraint-based-causal-structure-learning-with-consistent-separating-sets) | [code](https://github.com/honghaoli42/consistent_pcalg)

Verny L., Sella N., Affeldt S., Singh PP., Isambert H.; Learning causal networks with latent variables from multivariate information in genomic data;  PLoS Comput. Biol., 2017. [doi:10.1371/journal.pcbi.1005662](https://doi.org/10.1371/journal.pcbi.1005662)
