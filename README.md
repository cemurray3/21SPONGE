# 21SPONGE_tools

Simple tools for downloading, viewing and manipulating data from the 
21cm Spectral Line Observations of Neutral Gas with the VLA (21-SPONGE) 
survey at the Karl G. Jansky Very Large Array (VLA). 

The survey design and observational strategies can be found in 
[Murray et al. 2015](http://adsabs.harvard.edu/abs/2015ApJ...804...89M)
The final data release and spectral line decompositions can be found in 
Murray et al. 2018 (link TBD)

# Data

Download the data from the Harvard Dataverse (link TBD). 

Data for each target is stored in a fits binary table which includes the
21cm optical depth spectrum from the VLA (tau), the corresponding velocities 
for each channel (v_tau) and the velocity-dependent uncertainty spectrum (sigma_tau).
We also include the expected brightness temperature spectrum along each line
of sight (Tb), the corresponding velocities (v_Tb) and the the velocity-dependent
uncertainty in Tb (sigma_Tb), gathered from the literature 
(Heiles & Troland 2003, Winkel et al. 2016) or from the 21-SPONGE observing 
program at the Arecibo Observatory (Murray et al. 2015).

# Viewing and manipulating 21-SPONGE

A few examples of how to interact with the 21-SPONGE data
can be found in the Jupyter notebook.

# Getting Help

If you have any questions, please post an issue to this repository!



