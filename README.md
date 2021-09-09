# unitary-matrix-text-classification


## Authors
*Renan Cabrera (Algorithms)
*Stanley Salvatierra (Algorithms and implementation)


## Baseline

We take this example from PyTorch `https://pytorch.org/tutorials/beginner/text_sentiment_ngrams_tutorial.html` which is used as baseline for test the new proposed procudere for text classification.

## Datasets 

We take the example datasets provided by PyTorch in `https://pytorch.org/text/stable/datasets.html`

## Actual State

* The AGNews example is a multiclass classification problem, the method get stuck around 84% of accu. with N = 25.
* The other examples are binary class classification problem (0 or 1) , the method seems to work great with this kind of problems.
* The AmazonReviewPolarity requieres a lot of RAM (around 32 GB) because of the size of the dataset and the process of creating the token to unitary matrix maping. 
