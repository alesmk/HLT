# HLT Project

## Human Language Technologies 2023/24 Project

### Goal: _Cyberbullying Classification_

All pip needed is in a different file immediately inside the project folder.

Data preparation (folder):
    ⁃ Data_Analysis.ipynb
    ⁃ Data_Preprocessing.ipynb
    ⁃ Dataset_split_binary.ipynb

Data(folder): it contains our datasets

Classifiers (folder) : it contains all classifiers we tested
- NaiveBayes.ipynb

- LSTM_Multiclass.ipynb
- LSTM_Binary.ipynb
- Embeddings (folder): it contains two notebooks (FasttextEmbeddings.ipynb, BIN_FasttextEmbeddings) to create and evaluate the fasttext embeddings, the glove 50 and 200 embeddings and q&a file to test the embeddings. 
- Model (folder): it contains the most important models for NaiveBayes and LSTM.

All other files are related to Transformer Models:
- all files beginning with Grid + model name or Grid binary + model name contains the grid search for the given model 
- all files called Binary + model name or just model name contain the training and testing of the mentioned model

Grid search files about roberta and electra are very similar, and the same holds for the grid search files of BERT-based-uncased and BERT-large-whole-word-masking.

Training files:
- multiclass problem: bert-base and bert-large are very similar but separated in two different files - electra and roberta are very similar and in two different files
- binary problem: bert-base and bert-large are in the same file - electra and roberta are very similar and in two different files
