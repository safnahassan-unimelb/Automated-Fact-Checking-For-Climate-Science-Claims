
# COMP90042 Project 2023: Automated Fact Checking For Climate Science Claims


This folder contains all the code that has been used to develop the models used in the project. The 3 models explored are:
 1. NLP_with_Bert_and_FAISS: This model contains the implementation that uses FAISS indexing in a transformer for evidence retrieval along with a pretrained BERT model for claim classification.

 2. NLP_with_BM25: This model contains the implementation that uses BM25 ranking as the evidence retrieval function long with a pretrained BERT model for claim classification.

 3. NLP_with_BM25_and_2_Berts: This model contains the implementation that uses BM25 ranking as a filter of potwential evidences, and uses 2 pretrained BERT models, one for evidence retrieval using the potential filetered evidences, and the other BERT model for claim classification.

 To run any model, open the python notebook in Google Colab, and connect to GPU. Then just click on Runtime > Run All.

 All the data files should be stored in your "My Drive" in Google Drive under the following path: Sem 2/NLP /Assignment 3/project-data

