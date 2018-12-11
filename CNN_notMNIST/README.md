
## Context
This dataset was created by Yaroslav Bulatov by taking some publicly available fonts and extracting glyphs from them to make a dataset similar to MNIST. There are 10 classes, with letters A-J.

## Content
A set of training and test images of letters from A to J on various typefaces. The images size is 28x28 pixels.

## Acknowledgements
The dataset can be found on Tensorflow github page as well as on the blog from Yaroslav.

## Inspiration
This is a pretty good dataset to train classifiers! According to Yaroslav:

Judging by the examples, one would expect this to be a harder task than MNIST. This seems to be the case -- logistic regression on top of stacked auto-encoder with fine-tuning gets about 89% accuracy whereas same approach gives got 98% on MNIST. Dataset consists of small hand-cleaned part, about 19k instances, and large uncleaned dataset, 500k instances. Two parts have approximately 0.5% and 6.5% label error rate. I got this by looking through glyphs and counting how often my guess of the letter didn't match it's unicode value in the font file.

## Preprocessing
It was decided to use only part of the database. The set was divided into three parts. The learning choice consisted of 200,000 examples, cross validation of 15,000 examples, and 16355 examples for the test. The sets do not intersect, which makes the experiment clean.

## You can download a preprocessed data set
https://cloud.mail.ru/public/8zg5/goC6Rx4ZV


