## Overview
The classification approach was to use RoBERTa models for subjectivity detection and polarity detection. Separate models were built and trained using the combination of Stamford Sentiment Treebank (SST-5) and Financial Phrasebank datasets. These datasets are chosen as they contain positive, neutral, and negative sentiments, allowing for subjectivity and polarity detection. The subjectivity model achieved Validation Accuracy of 0.7824, Precision of 0.7909, Recall of 0.7824, and F1-Score of 0.7856. 


### Dependencies to install before running: 
numpy==1.26.4
torch==2.1.0
torchvision==0.16.0
torchaudio==2.1.0
transformers==4.41.0
tqdm
scikit-learn
matplotlib
pandas
seaborn
openpyxl

### Sources of datasets used for training 
The SST-5 dataset was downloaded from https://www.kaggle.com/datasets/haoshaoyang/sst5-data 

The Financial Phrasebank was downloaded from https://www.kaggle.com/datasets/sbhatti/financial-sentiment-analysis
