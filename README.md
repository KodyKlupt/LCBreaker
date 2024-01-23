# LCBreaker
To analyze liquid chromatography peaks, determine molecular weights, and predict protein concentration.

To use LCBreaker enter your data from your liquid chromatography machine (FPLC) in mL and mAU. A template CSV is provided. (See template.csv) 

## The LCBreaker works as following:
1. Adjusts the baseline to 0 mAU. (This can be removed)
2. Detects the peaks. Peaks are local maximas on the chromatogram. This data is outputted in a CSV format.
3. Determines peak area for determining total protein (being developed...)
4. For size exclusion chromatography, when using the slope and y-intercept from the linearized data from MW standards, determines the MW of the proteins.


