# TFIDF and cosine similarity - toy example
#### By Michael Preminger
#### Inspired by, and partly taken from the contributions of <a href="https://markhneedham.com/blog/2016/07/27/scitkit-learn-tfidf-and-cosine-similarity-for-computer-science-papers/">Mark Needham</a>  and <a href="https://towardsdatascience.com/tf-idf-for-document-ranking-from-scratch-in-python-on-real-world-dataset-796d339a4089">William Scott</a>

### This Notebook demonstrate the use of TFIDF in retrieval. <br> ~6000 very short documents (stored in the papers/ directory) are read into memory, preprocessed to various degrees and are indexed for retrieval.<br> 
#### A toy of a toy (10 documents) are available in the directory <b>papers1/</b>. To use it, change the following line in the first code cell of TFIDF.ipynb:
#### for file in glob.glob("papers/*.txt"): #"papers1/*.txt" - 10 documents ...