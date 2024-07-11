# Data-Manipulation_Py
This report describes a study carried out with data from procedural decisions, classified as "Granting" or "Denying", by the STJ. 

Using a 2000 sample texts and 200 embeddings, the study used Scikit Learn and Keras in Python for analysis and modeling. 
The data was pre-processed with techniques such as filtering, cleaning with regex, tokenization, translation, and text summarization, followed by vectorization with BigBird-Roberta-Base. 
The applied machine learning algorithm flattened the embeddings and used a Softmax layer for classification. 
The trained model achieved 75% accuracy and 728 loss after 700 epochs, resulting in the formation of 2832 clusters.
