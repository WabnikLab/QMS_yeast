# Microfluidics experiments

Microfluidics time-lapse videos are analysed using ImageJ. 

Selected regions of interest (ROI) from Channel002 (red channel) or Channel001 (green/blue channel) image sequence are analysed using an ImageJ macro script that gets the profile of each vertical line across the full width of the ROI of all slices of the video and generates a csv file with the intensity values,  one column per slice.

The .ipynb Python script cleans the csv data and generates plots for the analysis.
