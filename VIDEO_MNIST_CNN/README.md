### Input data

There is a video train.flv which displays a sequence of numbers with a frequency of 60 frames / sec from the MNIST database.
Labels numbers written in the file train_sequence.csv.
The task of recognizing the sequence of numbers in the video file test.flv is solved.

###  Description of the base.
The video stream is processed from the train.flv and test.flv files. Then the training sample and test are created. The training set consists of 42,000 examples. Test set of 5000 examples. Each frame has a dimension (56, 56).
