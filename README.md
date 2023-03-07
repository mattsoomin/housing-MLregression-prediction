
# Predicting House Prices with the Ames, IA Dataset
![](https://livability.com/sites/default/files/1Reiman%20Gardens.JPG)
_Courtesy of the Ames Chamber of Commerce_

#### Using the Streamlit Web App
1. Clone locally and install Streamlit Web: `pip install streamlit`
2. Navigate to project folder in CLI
3. Create a virtual environment with pipenv or conda env
4. `pip install requirements.txt`
5. `streamlit run SalePricePredictor.py`


### Project Outline
1. Import Housing data
2. Clean data
3. Perform Exploratory Data Analysis
4. Create a linear regression model that is highly accurate to predict sale price

### Repository Structure
**Folders**
- datasets : Datasets from Kaggle, as well as cleaned datasets produced from notebook and a data dictionary.
- images : Image files that have been produced by the project for presentation.
- models : Persisted models and other functions for inference and deployment.
- notebooks : Notebooks used to clean, analylze, and model predictions here.

**Notebooks**  
There are 2 notebooks with following purposes:
- Cleaning 
- Modeling

**Other Files**
- SalePricePredictor.py: Streamlit Web App for interactive predictions
