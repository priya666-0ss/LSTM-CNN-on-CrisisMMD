# LSTM-CNN-on-CrisisMMD

This repository is an implementation of LSTM-CNN model on CrisisMMD dataset for classification of 5 classes. 
I took 5 classes - (Hurricane Harvey, California wildfires, Mexico earthquake, Iraq-Iran earthquake, and Sri Lanka floods) and performed classification for given tweet and image.
I tokenised the tweets with the help of AutoTokenizer. It tokenized each tweet into array of length 100. Then I just passed them through LSTM encoder to get the tweet encodings.
Images are encoded with the help of VGG model.
Then Cnncatenated the tweet and image embeddings to pass them through fully connected networks to get the class prediction.

This model does the classification task but you can use the tweet and image embeddings to do many other tasks as well.
