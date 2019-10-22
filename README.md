# American National Parks' Biodiversity Analysis and Recreation Visits Prediction Based on Species Counts
Author: Yafei Ye, MRes Spatial Data Science and Visualisation, CASA, UCL

This project was written in Jupyter Notebook, and the ipynb file of this project is needed to be read in Jupyter Notebook as well.

The datasets used for this project are:

(1). 'species.csv' and 'parks.csv' downloaded from: https://www.kaggle.com/nationalparkservice/park-biodiversity. As this dataset was uploaded to kaggle in January 2017, I tried to find the newer one from the original source: https://irma.nps.gov/NPSpecies. However, I can only download the species list in every National Park one by one for I have to choose a park before searching data. After randomly choosing several parks to download the data and compare them with the dataset in Kaggle, I found they are totally the same. Now, I can make sure that the Kaggle one is the newest aggregation species dataset I can obtain.

(2). '2018 NPS Statistical Abstract.pdf' downloaded from National Park Service Data Store: https://irma.nps.gov/DataStore/Reference/Profile/2259799 which contains the 2018 Recreation Visits and Non-Recreation Visits (including commuters, government personnel and tradespeople with business in the park) statistics. Unfortunately, it's a pdf file and I typed the data manually and combined it with 'park.csv'.

Based on these data, this project's aims are:

(1). Exploring the biodiversity characteristics in every American National Parks deeply so that more visit suggestions can be given based on biodiversity;

(2). Finding relationships between total species counts and recreation & non-recreation visits counts to verify whether the amount of total species influences the number of visits;

(3). Building recreation visits prediction models based on different species categories data so that when building new national parks, the number of recreation visits can be predicted and more preparation can be made in advance.
