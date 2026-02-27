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

All final trained models in the ensemble can be found through these links too:
- RoBERTa model 0 (unweighted): https://drive.google.com/drive/folders/1nh-ESPiHG1gOZ7AWiPQIq3N2EUoFYA6h?usp=sharing
- RoBERTa model 1 (weighted): https://drive.google.com/drive/folders/14W4KNiSf31boAg6Zg-_NsQlWk9cfBDQd?usp=sharing
- RoBERTa model 2 (weighted): https://drive.google.com/drive/folders/1axeWHUrq0vS8YIhwKAKQ1kJvHCZSRykc?usp=sharing
- RoBERTa model 3 (focal): https://drive.google.com/drive/folders/1qw5p9jtck0liz2VoO8hy_pKTN7hyBwO7?usp=sharing
