======
HiSPoD
======
This program is developed for polychromatic x-ray diffraction of polycrystalline samples. 

Features
--------
Major capabilities include:
1. Simulate diffraction pattern of a given material2. Calculated radially averaged 1D diffraction profile from 2D diffraction data from APS 32-ID-B beamline.3. Index (hkl) of diffraction dataData to load
------------*.tif (series) files, *.tiff file or converted *.mat files*.txt file for energy spectrum (first column energy, second colomn flux)*.txt file for absorption (first column energy, second colomn transmission)Basic parameters
----------------1. Sample-to-detector distance: from sample to detector plane2. Detector angle: angle between detector plane surface normal and incident beam3. Pixel size: assuming square pixel shape4. Scaling factor: data binning factor, used for accelerating analyis speed5. Image dimension: pixel numbers of the detector6. Number of  harmonic peaks: how many harmonic energies users would like to consider when labeling the (hkl) peaks7. Direct beam X and Y (optional): direct beam position on detector, could be negative number. If not known, users can use "Find (00)" tool to estimate them.8. Content in "Sample structure" module: weight of diffraction intensity of each phase in the overall diffraction pattern. This is not the mass or mole content, instead, it's simply a parameter to for data fitting. Without input, the default is 50% for each.9. Points in "Tools" module: Number of point for scattering vector q in I(q) (and I(tth)) plots.10. Q res in "Tools" module: half width of q window when performing radially average. The larger the number, the smoother the intensity profile. It should be equal or slightly larger than the half of the difference of adjacent q points.Sample structure information
----------------------------Users need to input sample crystal structure and reference diffraction information for using "Simulate diffraction" and "Label (hkl)" tools. 
