# word2vec-explore
Playing around with word2vec vectors in jupyter notebooks. Presentation prepared for PyData Warsaw 2017. 

Download vectors from [GloVe](https://nlp.stanford.edu/projects/glove/), put them in `data` folder. You might need to do `sed -i '9d' file.txt` to remove the 9th line (it's the vector for ", so it isn't of much interest, but gives some trouble with parsing.
