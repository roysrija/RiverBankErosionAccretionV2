# RiverBankErosionAccretionV2
RiverBank Erosion and Accretion – Version 2 is an advanced QGIS plugin developed to identify, quantify, and visualize riverbank changes (erosion and accretion) between two temporal datasets. It supports river morphology assessment and aids in sustainable river basin management.
Key Features:

Automated detection of erosion and accretion zones from multi-temporal river layers

Support for vector and raster-based spatial datasets

Interactive interface with simplified input selection and process execution

Visualization of change maps with area statistics

Option to export outputs as shapefiles and CSV reports
Requirements:

QGIS 3.10 or higher

Python 3.x

Required libraries: geopandas, numpy, shapely, matplotlib

How to Use:

Load the two river shapefiles representing different time periods.

Define the output directory for processed files.

Run the analysis to compute erosion and accretion areas.

View and export the resulting change maps and summary statistics.

Output Files:

Erosion_Areas.shp – Polygons indicating eroded regions.

Accretion_Areas.shp – Polygons indicating newly formed land areas.

Summary_Report.csv – Tabular statistics of area changes.

Credits:

Developed by Dr. Srija Roy
