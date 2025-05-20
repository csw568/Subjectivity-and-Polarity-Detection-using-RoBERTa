Dependencies to install before running: 
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

The classification approach for Q4 was to use RoBERTa models for subjectivity detection and polarity detection. Separate models were built and trained using the combination of Stamford Sentiment Treebank (SST-5) and Financial Phrasebank datasets. The trained models were then combined into one pipeline to perform subjectivity detection, filter the data of those labelled as 'neutral', followed by polarity detection on the data labelled as 'opinionated' for the EV dataset crawled from Reddit. 

The SST-5 dataset was downloaded from https://www.kaggle.com/datasets/haoshaoyang/sst5-data 
The Financial Phrasebank was downloaded from https://www.kaggle.com/datasets/sbhatti/financial-sentiment-analysis