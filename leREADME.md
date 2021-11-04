The purpose of the notebook is to visualize structures around a galaxy cluster, for which the RA/Dec is already known (in this case: 55.7506655, -32.2722637).

The Butler is used to make a color image of the cluster core we'll analyze; from tutorial 01 and tutorial 03a
The TAP service is used to make a table of bright galaxies around an apriori known z~0.2 cluster core; from tutorial 01
A color-magnitude diagram of the galaxies of the core, as well as surrounding regions is plotted from the tabular data; from tutorial 02
The color magnitude diagram is used to choose red sequence galaxies.
An adaptive kernel technique is used plot the red-sequence galaxy density and visualize the large scale structure of the red members. The truth tables are used to compare the large-scale structure based on redshifts.
The notebook utilizes aspects from tutorial notebooks 2-5.

It then uses an adaptive kernel technique to plot the red-sequence galaxy density to visualize the large scale structure based on red sequence membership. Finally, it uses the truth tables to compare the large-scale structure based on real redshifts. The kde is calculated using seaborn as well as scipy.stats
