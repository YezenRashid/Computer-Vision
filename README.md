# Computer-Vision

This is written in c++.

The goal of this project was to modify the original SIFT code in opencv so that normalization is performed after stacking.
The original SIFT code normalized each color band and then stacked them.  We aimed to first stack the color bands and then 
after they are all merged, we then apply the normalization.  After completing the code and getting the precision recall 
curve results, we compared the results to the same SIFT and Opponent SIFT results to see how well it performed on different 
image sets.

