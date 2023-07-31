Steam Game Recommender System
BrainStation Capstone Project
-----------------------------
Author: Annie Yan
Date: July 31, 2023
Email: annie.yq.yan@gmail.com
-----------------------------


--------------------------------
RUNTIME ENVIRONMENT REQUIREMENTS
--------------------------------
Please refer to the requirements.txt file for specific python libraries that will be required. 


-------------
DATA SOURCING
-------------
Raw Data Files: (~ 710MB .zip)
--------------
https://drive.google.com/file/d/1Jn0d5HI6BJkFT5DDNki6ZgC6HujPJ3mG/view?usp=sharing

At minimum, please download the raw data files at the Google Drive linked above. While data has been derived from Kaggle (and relevant linked include in Notebook Part 1), the naming schemes of some files have been changed for clarity. 

Cleaned Data File: (~ 1.14GB .zip)
-----------------
https://drive.google.com/file/d/1SkUIx5ozOfoT1KBjf4WxtGlpXd5RDKuI/view?usp=sharing

The cleaned version of all datasets can be accessed at the above Google Drive link. 


-----------------
JUPYTER NOTEBOOKS
-----------------
Part 1: Data Pre-processing
---------------------------
This notebook addresses the data sets being used and the intial, extensive data cleaning process that was completed.

Part 2: Exploratory Data Analysis and Visualizations
----------------------------------------------------
More data cleaning and wrangling was done in this notebook based on the results of the exploratory data analysis. Visualizations were incorporated and discussed amongst the additional cleaning process.

Part 3A: User Independent and Cosine Similarity Recommendation Modeling
-----------------------------------------------------------------------
Creation of basic recommendation models, with discussion--primarily, score-based recommendations for cold starts. Additional cosine similarity model was created using game data information and game description information. Multiple sample tests were done. The cosine model within this notebook takes a significant amount of time to run, and it should be noted that it requires at least 32GB of RAM to comfortable run. Certain variables can be adjusted to assist with running on lower spec machines, but the runtime will take longer. 

Part 3B & 4:  K-Means, Cosine Similarity and FunkSVD Modeling & Evaluation
--------------------------------------------------------------------------
Creation of a hybrid recommendation model that incorporates an initial K-Means clustering and a subsequent cosine similarity of clustered games. A truncated dataset was used to preserve computational resources, though it should be noted that this notebook still requires signficant computing power. Additionally, a FunkSVD model was created using user recommendation information and briefly discussed. 

