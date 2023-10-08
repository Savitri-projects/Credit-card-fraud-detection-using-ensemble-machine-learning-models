
# Credit card fraud detection using ensemble machine learning models

This project involves a comparative analysis of three Machine Learning models: one using oversampled data, another with standardized data, and the third with standardized, oversampled, and denoised data using an autoencoder, all inputted into an ANN model. We assess and compare these models at nine threshold values ranging from 0.1 to 0.9. The dataset chosen for this analysis is "credit card fraud detection" from Kaggle, and we calculate the AROC score to gauge model accuracy due to the data's significant imbalance. This versatile algorithm can be applied to various datasets, particularly those with imbalanced distributions.

## How to use it

1. First clone the repository with 
`git clone https://github.com/Savitri-projects/Credit-card-fraud-detection-using-ensemble-machine-learning-models.git` command

2. Worth taking a look at `PPT.pptx` and `Report.pdf` to understand many things

3. First you will need jupyter notebook working. Check [this](https://docs.jupyter.org/en/latest/install/notebook-classic.html) for jupyter notebook installation. Basically, it asks you to install anconda from [here](https://www.anaconda.com/download)

4. Once you have jupyter notebook ready, it will open a browser tab with a home page with all the files present.

5. Unzip `creditcard.zip` file and upload the csv file: `creditcard.csv` along with the three ipynb files: `1_Direct_ANN.ipynb`, `2_Standardization+ANN.ipynb` and `3_Autoencoder+ANN.ipynb` into the notebook. 

6. Now your are good to go 🥳🥳. Open each of the ipynb files, understand and experiment with them.
## What to check in this

1. Begin by comprehending 
  * the imported libraries
  * data input methods
  * standardization
  * oversampling techniques
  * ANN model construction (including layer additions)
  * confusion matrix creation
  * understanding the concept and utility of autoencoders
  * grasping the significance of the AROC score, and the rationale for its preference over accuracy

2. You can find information on these topics in online sources, the provided PowerPoint presentation, and the mentioned report.

3. Now run each and every block in each of the notebooks. You might encounter a few issues with the first block of importing the libraries, but they can soon be solved with the online help

4. Most of the issues that we get are because of version differences of libraries - and they change a few module names in each version.

5. You would get different accuracy values that what are there when you first open the file. But that is expected and the you should actually get similar values.

6. The final results should look similar to these values: 



| Threshold | ANN applied on autoencoder | ANN on scaled data | ANN on oversampled data |
|-----------|---------------------------|--------------------|-------------------------|
| 0.1       | 0.9436                    | 0.9213             | 0.5                     |
| 0.2       | 0.9398                    | 0.9113             | 0.5                     |
| 0.3       | 0.9406                    | 0.8978             | 0.5                     |
| 0.4       | 0.9411                    | 0.8842             | 0.5                     |
| 0.5       | 0.9416                    | 0.8672             | 0.5                     |
| 0.6       | 0.9419                    | 0.8571             | 0.5                     |
| 0.7       | 0.9371                    | 0.8435             | 0.5                     |
| 0.8       | 0.9373                    | 0.7959             | 0.5                     |
| 0.9       | 0.9383                    | 0.7482             | 0.5                     |




## Enhancements/ Research that you can do

1. There are many enhancements possible

2. Try making the model even better to get good AROC scores

3. Find other datasets and try employing this with them

4. Understand why this approach is better than other powerful algorithms like random forest, SVM etc., 

... and many more

Thanks for coming here!!