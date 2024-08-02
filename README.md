# getslmem
The R Package *getslmem* provides a toolkit for the stimation and General-to-Specific (GETS) modelling of logarithmic Multiplicative Error Models (MEMs) with covariates ('X'), log-MEM-X in short. MEMs are robust and flexible models for non-negative variable like, for example, volatility, volume, prices and the unemployment rate. Both static and dynamic MEMs can be estimated. GETS modelling is a powerful variable selection algorithm that returns a parsimonious model with the variables that matter the most.

# Installation
The package *getslmem* requires version 0.39 of the package *gets*, which is under development (that is, version 0.39 is not on CRAN yet). The following code can be used to install *gets* version 0.39 from Github:

    install.packages(
      "https://github.com/gsucarrat/gets/raw/master/gets_devel.tar.gz",
      repos = NULL, type = "source"
    )

Next, to install *getslmem*, use the following command:

    install.packages(
      "https://github.com/gsucarrat/getslmem/blob/main/getslmem_1.0.tar.gz",
      repos = NULL, type = "source"
    )
