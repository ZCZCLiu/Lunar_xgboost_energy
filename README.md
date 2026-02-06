# Lunar_xgboost_energy
XGBoost regression on local reaction energies
# User Guide
The folder contains 3 notebooks for the XGBoost regression and SHAP analysis:
1. xgboost_dE_H.ipynb: the H insertion energy (H + MOx---> HMOx);
2. xgboost_dE_H2O.ipynb: the H2O formation energy (recombinative desorption, 2HMOx ---> MO + MO1-x + H2O);
3. xgboost_dE_H2O_1.ipynb: the H2O formation energy (H + HMOx ---> MO1-x + H2O).

The corresponding target energies and features are stores in 3d_H, 3d_H2O, and 3d_H2O_1, respectively.

H_binding_sites.xlsx: the H bind site information including chemical formula, supercell, Materials Project ID, symmetry, and H binding sites predicted by SoftBV.


# Acknowledgements
This work was supported by the government of Canada through the NFRF Exploration program.
