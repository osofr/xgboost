# INSTALLATION INSTRUCTIONS for xgboost:

1. Clone the local repo at:

2. Follow these instructions to install OpenMP enabled compiler on your system:
https://github.com/Rdatatable/data.table/wiki/Installation#openmp-enabled-compiler-for-mac

3. Compile the xgboost C++ libraries with: make -j4

4. Compile the xgboost R-package with: make Rbuild

5. Install the final source package with: R CMD INSTALL ./xgboost_0.6.4.6.tar.gz

6. Alternatively, can use:
install.packages("/Users/olegsofrygin/GoogleDrive/Alex_SDR/xgboost/xgboost_0.6.4.6.tar.gz", repos = NULL)