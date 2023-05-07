# CS 598 Paper Reproduction Code (by Regan Brown)
Each experiment for this paper is in a different notebook; however, most of the code is the same between them. Please refer to the included Jupyter notebooks for both the source code and detailed instructions and explanations on running it. **These are not descriptive notebooks; they are my full source code combined with text that would normally be in this README. I find this easier to follow along with as code and explanation are in the same place.** Basically, you can run the code for the notebooks as you would for any other notebook, provided the following requirements are present:  

Python 3 (I used version 3.10.9) and the following additional, nonstandard Python libraries:  

-nltk v3.7  

-datasets v2.11.0  

-pandas v1.5.3  

-numpy v1.23.5  

-gensim v4.3.0  

-pytorch v1.12.1  

-scipy v1.10.0  

-tqdm v4.64.1  

NOTE 1: In order to run the code in the Jupyter notebooks successfully, you MUST follow the instructions here to set up the Stanford Parser NLP server:
https://github.com/nltk/nltk/wiki/Stanford-CoreNLP-API-in-NLTK  

NOTE 2: For Experiment 2, the STS Benchmark dataset from 2017 is required. You may download it yourself from https://ixa2.si.ehu.eus/stswiki/index.php/STSbenchmark. Alternatively, I have uploaded a copy of the train and test datasets in CSV format to this repo. The filepath in my Experiment 2 notebook refers to the directory on my local machine where I stored these files; please redirect it to the appropriate path on your machine before running. (Filepath is clearly commented in notebook.)
