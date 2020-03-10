# Kaggle Competition Titanic Dataset

## Topics Covered
- **Feature Analysis** using the following methods:
  - Correlations
  - F Score
  - Mutual Information
  - Chi Test
  - Principal Component Analysis(PCA)
- **Logistic Regression** with **Feature Selection**
  - Logistic Regression for different scoring functions
  - Feature selection using **Recursive Feature Elimination(RFE)**
  - **Receiver operating characteristic(ROC)** with AUC
  - Handling missing values, categorical values and Standardisation

## How to run
1. Build docker image
   
   `docker build -t kaggletitanic .`
2.  Run docker container

    `docker run -it -v $(pwd):/workdir -p 8888:8888 -t kaggletitanic`
3.  From inside the container workdir run to start jupyter notebooks

    `jupyter-notebook --ip='0.0.0.0' --port=8888 --no-browser --allow-root`

## Resources
- [Dataset](https://www.kaggle.com/c/titanic/data)
