Description
-------------
Jupyter notebook code can be found under notebooks. The LSTM and BERT models are trained and made to output a model file 'mood_navigator.pkl' which will be used in the streamlit app along with emotion
dataset to achieve the most accurate result possible. This is a fusion of LSTM/BERT model training along with already available datasets being used together in unison to provide an intuitive app
in the form of a Streamlit app for the end users to retrieve accurate readings of their emotion using machine learning and natural language processing.




Instructions to run the Streamlit App are as follows:-
--------------------------------------------------------
1) pip install -r requirements.txt

2)streamlit run app.py 




requirements.txt 
-----------------
numpy
pandas
seaborn
neattext
plotly
scikit-learn
joblib
