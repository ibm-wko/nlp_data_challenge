# Data Challenge (2-3 Days)
## Get the data
We will be using the Neural Information Processing Systems (NIPS) 2015 conference papers as a text corpus. These can be obtained off Kaggle, which requires that you create a free account, at [this link](https://www.kaggle.com/benhamner/nips-2015-papers/version/2). An [overview](https://www.kaggle.com/benhamner/nips-2015-papers/version/2/home) talks about the data, which is available as a csv, in raw form from the PDFs, and also already stored into a sqlite db.

## Tasks
Although we are only going to be working with the NIPS dataset, consider that this might be used later on to process a dataset much larger (eg an entire subreddit or all the articles from a news publication). Your ideas should be reusable and scaleable. Final work should be in commandline executable form and should allow the user to start with the files mentioned above and do all the following tasks.

### Generate FastText word embeddings
One of the standard building blocks in NLP is the word embedding. The gold standard used to be word2vec embeddings, however we will be creating FastText embeddings instead due to their ability to deal with out-of-vocabulary words. Ensure that you can support a user-defined number of dimensions and have the ability to turn on/off at least one text-preprocessing step.

### Generate a list of keywords
Within every text corpus, there are certain keywords that are specific to that corpus. Although keywords may normally be monograms, be sure that your methods can identify at least bigrams as well.

### Group the documents
In addition to keywords, a corpus will generally have clusters of topics. Group the documents together (ie output groups of document titles) and identify how they are grouped.

## Additional Info
Logical organization and comments help to make code more understandable and maintainable. Keep this in mind as you write your code! Feel free to use any packages that you would like. Please check all your code into a publicly accessible Github repo.
