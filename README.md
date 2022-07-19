# Sarcasm_detector
<img src = "https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTNa4s0jCmSWI1T7Tp_FEYUmpzRRDISpZbSTdzx214Yztkf0uDV8p5B1sOkGRAin7VGPiE&usqp=CAU"/>

## Installations
 - NumPy
 - Pandas
 - Seaborn
 - Matplotlib
 - Sklearn
 - Pickle
 - XGBoost
 - SHAP
 - Wordcloud
 - NLTK
 
## Project Motivation
Objective of this project is to build a sarcasm detector which detects whether a news headline is sarcastic or not? Application of this model can be to filter out sarcastic news headlines from serious ones and help news curating organizations and pages in shortlisting relevant news articles.

## Files structure
<ul><li><b>Data</b></li>
<ul><li>Sarcasm_Headlines_Dataset.json - JSON file with headlines data</li>
<li>Sarcasm_Headlines_Dataset_v2.json - Additional file with few extra rows</li></ul>
<li><b>Output</b></li>
<ul><li>Output files into a zip format - compressed due to limitation of file upload on github</li></ul>
<li><b>Models</b></li>
<ul><li>count.pickle - Pickle file of BagOfWords vectorizer</li>
<li>tfidf.pickle - Pickle file of TF-IDF vectorizer</li>
<li>model_tfidf.pickle - Pickle file of final best model</li></ul>
<li><b>Sarcasm_Detector.ipynb</b> - Main coding notebook</li></ul>

## Results
The main findings of the code can be found at the Medium Blog post available [here](https://medium.com/@harshitkapoor_73807/is-this-sarcasm-8fed766f6033) explaining the highlights of my project.
A XGBoost Classifier was chosen to be the best model by evaluating F1 score and accuracy metrics. The final model achieved an F1 score of 67.9. 

## Acknowledgements
Data downloaded from Kaggle - [here](https://www.kaggle.com/datasets/rmisra/news-headlines-dataset-for-sarcasm-detection?resource=download)
