# scope2elecsus
Laser spectroscopy of hot atomic vapours: from ’scope to theoretical fit Notebook

In this folder is the data and Jupyter notebook (python 3) to process the data presented in the paper "Laser spectroscopy of 
hot atomic vapours: from 'scope to theoretical fit". 

Running the notebook will generate figures 8, 9, 10 and 13. The steps of how to process the data to the form plotted in these 
figures is clearly outlined throughout the notebook, with reference to sections in the paper. 

# Required Modules
- python 3.9 (ElecSus is not currently supported on python 3.10)
- NumPy
- Matplotlib
- SymPy
- SciPy Library 0.15.0 or later
- lmfit 0.9.5 or later
- ElecSus v3.1.0 (Download at https://github.com/durham-qlm/ElecSus)
- Optional: wxpython (To fit data using GUI shown in Figures 11 and 12)

# Description of Files in Folder

Below listed are files in this folder with a short description.
Keywords: raw, linearised, normalised etc. are all outlined in the notebook and the paper.

Dopp_Broadened_20C.csv : This is the raw data for the Doppler broadened spectrum at 20 degrees Celsius.

Dopp_Broadened_40C Norm.csv : This is the normalised data for the Doppler broadened spectrum at 40 degrees Celsius.

Dopp_Broadened_73C Lin.csv : This is the linearised data for the Doppler broadened spectrum at 73 degrees Celsius.

Dopp_Broadened_73C Norm.csv : This is the normalised data for the Doppler broadened spectrum at 73 degrees Celsius.

Etalon.csv : This is the raw data for the etalon, recorded simultanously with 'Dopp_Broadened_20C.csv' above.

Sub_Doppler Spectrum.csv : This is the raw data for the sub-Doppler spectrum, recorded simultanously with 'Dopp_Broadened_20C.csv' above.

Notebook_Tutorial.ipynb : A Jupyter notebook (python 3) to process the data above and output figures 8, 9, 10 and 13. The Jupyter notebook takes the reader step-by step through the data processing from raw data to a state in which it can be compared with theory.

# References
Laser spectroscopy of hot atomic vapours: from ’scope to theoretical fit
  Notebook Download: https://github.com/durham-qlm/scope2elecsus
  Paper: XXX (Not yet published)

ElecSus
  Download: https://github.com/durham-qlm/ElecSus
  Papers: https://www.sciencedirect.com/science/article/pii/S001046551400407X, https://www.sciencedirect.com/science/article/pii/S0010465517304009

