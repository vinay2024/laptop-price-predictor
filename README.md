Laptop-price-predictor

Dependecncies to install
streamlit
scikit-learn
xgboost

app.py contain the code of streamlit


If you get these errors

1. It will give an error if you'r using the latest version of scikit-learn. So downgrade the version using pip install scikit-learn==1.2.2

2. If you get this error
ModuleNotFoundError: No module named 'pandas.core.indexes.numeric'
then pip install pandas<2.0.0
