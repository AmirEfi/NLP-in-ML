# NLP-in-ML
## Final Project of Machine Learning course - Fall 2023
This repository is for natural language processing in Persian with ML.

The roadmap is as follows:

![image](https://github.com/user-attachments/assets/6f0ecb64-5cf1-4906-9d0e-48405ba89d6f)

In the NLP.ipynb file, I did the step-by-step process as in the photo.

The [dataset](https://drive.google.com/file/d/1gyEAly-tnTr3NRkvNGHmn0_77s3nyfDU/view) I used was texts of the news with the category of them.

First of all, preprocessing was done on the texts. then the words are tokenized. now feature extraction has been applied by using the TF-IDF method and finally, the random forest is selected to use in the machine learning model.

In the end, the model must be capable of determining the category of random news.

Also, you can see the results of some usual metrics in the final lines of the code.

First of all, to use this model you have to get the news text, and then pass it to the primray_prep_text function to remove punctuations. after that, pass it to the remove_stopwords function to remove stop words. now give this clean text to the [TF-IDF model](https://drive.google.com/file/d/1yuVAFnBFuI-c37-8n8XHQeDsIjOakQA7/view?usp=sharing) to extract features and so give the features to the final [model](https://drive.google.com/file/d/1kflWvXH8ZYmAKwoPeQROKh25IVWv3IPX/view?usp=sharing) to provide you with the probable category the news may contain.




