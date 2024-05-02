# CV-for-hedgerow-loss
Files for identifying and mapping historic extents of the hedgerow network with CV processing of historic OS maps. 

About the three script files:
I have condensed the majority of my code into two scripts. The first is called "12  County Map Sheets.ipynb" which encompasses the entire pipeline of my model from downloading OS maps from an online repository, combining these and georeferencing them, annotating the individual images that were segmented from these larger maps, and training a CNN to classify each based on semantic labels. The file "Multiple_layers.yaml" is necessary for defining the annotation task for creating the labeled training dataset. The second script called "statistics_and_analysis.ipynb" is all the data analysis I carried out once successful model results were produced.
