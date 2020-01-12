## NFL big data bowl (53th place private solution)
Solution for the NFL competition on Kaggle https://www.kaggle.com/c/nfl-big-data-bowl-2020/discussion. The last version is code/solution_v5. 

The key points of the solution - single lightGBM classifier model with pitch-control based features (ifo_rusher_pc_...). Code for preprocessing and class describing a model is from popular public kernels. For the feature selection, 2 techniques are used - simple FS based on LightGBM's feature importance and custom FS method based on refitting the model without each feature and comparing the results with the model fitted on the full set of features.   
