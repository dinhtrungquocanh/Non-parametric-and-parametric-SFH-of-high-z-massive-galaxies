# Non-parametric-and-parametric-SFH-of-high-z-massive-galaxies
This is the code for my bachelor thesis: Star Formation History of Massive Galaxies at z > 3. I conducted the SED fitting with Bagpipes and used 3 different SFH models: delayed tau, double power-law and non-parametric using continuity priors. 

My thesis advisor: Dr. Abdurro'uf (Indiana University).  

Further information and examples of Bagpipes (Carnall+2018) can be found here: https://github.com/ACCarnall/bagpipes/blob/master/examples/

The SED Fitting using 3 SFH models is featured in the file 'SED_Fitting_3_SFH_Models.ipynb'. This notebook covers the fitting for an indivisual galaxy in the sample 'all_candidates_cat.csv'. The photometry data for the example galaxy is from the file 'phot_results_20.csv'. 

You can check my repository on the aperture photometry with Photutils: https://github.com/dinhtrungquocanh/Aperture-Photometry-for-Galaxies-with-Photutils

For further analysis and timescale calculation are included in the file 'Timescale_Calculation.ipynb'. In this notebook, we focus on analyze 1 massive quiescent galaxy and 4 rejuvenating candidates. Some of these are not included in the 'all_candidates_cat.csv' but in the 'new_candidates.csv', which is an additional sample that was added later in the project. 

Some helpful references:
- Carnall, A. C., McLure, R. J., Dunlop, J. S., & Davé, R. (2018). Inferring the star formation histories of massive quiescent galaxies with BAGPIPES: evidence for multiple quenching mechanisms. Monthly Notices of the Royal Astronomical Society, 480(4), 4379-4401.
- Carnall, A. C., Leja, J., Johnson, B. D., McLure, R. J., Dunlop, J. S., & Conroy, C. (2019). How to measure galaxy star formation histories. I. Parametric models. The Astrophysical Journal, 873(1), 44.
- Leja, J., Carnall, A. C., Johnson, B. D., Conroy, C., & Speagle, J. S. (2019). How to measure galaxy star formation histories. II. Nonparametric models. The Astrophysical Journal, 876(1), 3.

