# ErdosTeamViper
This is Team Viper's final project for the data science bootcamp organized by the Erdos institute. Our team members are Cynthia Lester, Sanal Shivaprasad, and Ignat Soroko.  Click [here](https://raw.githubusercontent.com/sanalsprasad/ErdosTeamViper/main/Presentation/video.mp4)  for a 5-minute video presentation of our results. 

## Project Summary
- Goal is to predict the cuisine type of a recipe based on the list of ingredients.
- Data set is from an old Kaggle competition: <https://www.kaggle.com/competitions/whats-cooking>

## Results
The most accurate model was a Linear Support Vector Machine with C = 0.1 using the train_trimmed data set. Note: only key_words_data and train_trimmed were used for this determination.

## Repository Layout
### Data Folder
- Contains three cleaned training data sets: key_words_data.zip, removed_adj_data.zip, and train_trimmed.csv
- Original training data is contained in train.json
- Jupyter notebooks are related to obtaining the cleaned data sets and exploring the data.

### Models Folder
- Our search for the best model (based on overall accuracy) using k-fold cross-validation.
- Jupyter notebooks showcase the results of various models.

### Presentation Folder
- Contains a 5-minute video presentation of our results, the slides and an executive summary. 
