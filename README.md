ROIpixelCount
=============

Download zipped files; unzip files on local computer; place files on Matlab path

1. Run ROIPixelCount from Matlab command window

** Only load images that have the region of interest (ROI) to be traced

2. Select File Options from menu and select 'Load Image Series'
3. Select directory with files from dialog box
4. List of images will populate file list and first image will automatically load with name
5. User can select which RGB channel to view 
6. To start quantification, select Start Analysis from Analysis Options drop down menu
7. Select Pixel Count from Analysis Options drop down menu
8. Select which RGB channel to trace nucleus ROI
9. Indicate which channels are to be analyzed; and identify those labels
10. First the program will require that you trace the ROIs in each image and will calculate a pixel intensity
    threshold based on an aggregate pixel population from all traced regions for each channel selected for analysis.
11. After threshold has been derived the program will start at the first image and present the channel selected for tracing 
    with inverted grayscale to enhance contrast
12. For each image retrace the ROI
13. GUI will display values for pixel number in side data table
14. When user has completed the series the GUI will prompt the user to export the data
15. Select export option (Matlab or Excel) from Export Options

email questions, errors, bugs, suggestions for improvement or features requests to:
     john (dot) arthur (dot) thompson (at) gmail (dot) com
