# Imperial College London Natural Language Processing Coursework 2026

This coursework explores the use of a RoBERTa ensemble for Patronizing and Condescending Language (PCL) detection.

- Due to the large size of RoBERTa models, they are not present within the ```BestModel``` folder, but the notebook to train and run these models ```pcl_ensemble.ipynb``` is present.
- Final predictions for the dev set and test set are found in their corresponding text files in the ```predictions``` folder.

If running locally:
- Install the packages in ```requirements.txt``` into a virtual environment.
- Set the variable at the top of the notebook to ```LOCAL```.

If using Google Colab:
- Copy all datasets and train/dev/test splits into folders in Google Drive ```/content/drive/MyDrive/pcl_datasets```
- Models and predictions will be saved into a folder in Google Drive according to the paths at the top of the notebook.

This repository also contains the notebooks used for EDA and error analysis which are correspondingly named.
