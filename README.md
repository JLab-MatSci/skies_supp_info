# skies_supp_info

In this example basic features of SKiES code are presented.

To see its main features, please follow the instructions given
in the manual, section 2 "Running examples". One has to download
one or both of the following archives:

$ wget -O Ag_epw_prep.tar.gz https://www.dropbox.com/scl/fi/16e9cxbpreffpb2ombcwm/Ag_epw_prep.tar.gz?rlkey=afls5pyqpdsxov995tvlunisl&st=tkh0qxtu&dl=0
$ wget -O Ag_no_epw_prep.tar.gz https://www.dropbox.com/scl/fi/26ub5zl6gys8cetgrvsz8/Ag_no_epw_prep.tar.gz?rlkey=k0d3zimcaz0nwyuw2fqyisfqn&st=1lekmkm3&dl=0

and extract the contents:

$ tar -xzvf Ag_epw_prep.tar.gz
$ tar -xzvf Ag_no_epw_prep.tar.gz

The first folder contains the files obtained as byproducts of
Quantum Espresso EPW execution, so its fully prepared for
direct usage of SKiES. The second folder only contains input
Quantum Espresso EPW files to run preliminary ab initio calculations.
See the details in the corresponding README files located in each folder.
