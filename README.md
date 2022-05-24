# Master_Thesis

This repository contains raw data and programming code that was used for modelling part of Denis' Bondarenko Master's Thesis. 
Repository contains 3 Python (Jupyter Notebook) scripts input files and resulting files.
Inputs files are:
aaa_bonds.xlsx, aa_bonds.xlsx, a_bonds.xlsx, bbb_bonds.xlsx, bb_bonds.xlsx, b_bonds.xlsx - list of all bonds with corresponding rating as of Jan 2022 from Cbonds.Ru. No downgrades were revealed during 2020-2022, which means these 6 files contain full list of russian rated bonds.
Flags_info.xlsx - information regarding state affiliation of the issuers, according to Cbonds.Ru.
dynamic-2.csv - historic parameters for MOEX G-Curve, downloaded from MOEX.
Coupons - folder containing payment schedules for all bonds, sourced from Cbonds.Ru.
Ratings - folder containing historic rating info from both AKRA and Expert RA rating agencies, sourced from Cbonds.Ru.
Quotes - folder containing trading info results with closing bid-ask spreads, from Cbonds.Ru.

Resulting files are: 
trades_info.xlsx - resulting file from script 0. Preliminary analysis.ipynb. Contains information regarding trades of bonds in scope.
Inputs_for_modelling - folder contains files with calculated variables for model estimation
Model1 and Model - folder with results of modelling. Contains both raw results from script 1. Curves Estimation.ipynb and aggregated results from 2. Tables and figures.ipynb.

Files are to be used as they are located. 

