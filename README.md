# LU_Classification_R
Land Use Classification using Landsat 8

The land use classification was implemented using random forest machine learning algorithm. The image was classified into 6 classes:
1. Water
2. Forest
3. Plantation
4. Crops
5. Built-up
6. Bare land

The 1st step is to extract the NDVI, NDWI, and NDBI from Landsat 8 in the study area.
The 2nd step is to stacking to all the .tiff files into a single .tiff file which is involve the use of bands from band 2 to band 7, NDVI, NDWI, and NDBI.
Then the stacked file will be used to predict 6 land use classes using random forest algorithm.
