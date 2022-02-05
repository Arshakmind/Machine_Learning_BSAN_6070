# readme
This notebook is an Exploratory Data Analysis (EDA) of Indian Pollution Data on air quality. Please see for more [context](https://github.com/Arshakmind/Machine_Learning_BSAN_6070/blob/main/CA01/CA01_EDA_India_Pollution_Instructions.pdf).
![air_pollution](https://user-images.githubusercontent.com/59128920/152625918-f073e29d-b781-4ccc-97d1-2c8374dc44ee.png)


![data head()](https://user-images.githubusercontent.com/59128920/152625741-163ebfb0-8857-456e-a5b5-4e067963f5b9.png)


## Runtime

3-10 sec

## Required libraries to run the notebook

1. [pandas](https://pandas.pydata.org/)
2. [numpy](https://numpy.org/)
3. [scikit-learn](https://scikit-learn.org/stable/)
4. [matplotlib](https://matplotlib.org/)

Please make sure to have these installed and imported to run the notebook. 

## Dataset

The dataset should be located in the same folder with the notebook.

    #read dataset
    data = pd.read_csv('data.csv', encoding = "ISO-8859-1", low_memory = False)
