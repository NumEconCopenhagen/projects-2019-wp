# Dataproject

This project focuses on wind enery in Denmark. We will create an interactive map which shows each municipalities contribution to the transistion towards a greener future.

We use several packages such as pandas, matplotlib.pyplot, numpy and geopandas - geopandas is an extension which needs to be installed to be able to run the codes. 

The dataset is located in an excel file called "anlaegprodtilnettet.xls" which has been uploaded.

The way to run the code is to:

1. Import all the packages needed - geopandas should be installed if you don't already have it. To install geopandas write conda install -c conda-forge geopandas in terminal (mac).
2. Import data from excel
3. We drop all wind turbines less than 25 kW as they are characterised as household wind turbines.
4. We then rename the columns called 'Unnamed: x' after the import from excel to pXXXX as an indicator for the production in a given year.
5. Plot the number of existing wind turbines in a given year connected to a grid.
6. We look at the evolvement of the average capacity per wind turbines in a given year.
7. At last we create an interactive map of Denmark with information regarding wind energy. 