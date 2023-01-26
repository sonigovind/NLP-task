# NLP-task
I will be exploring N-gram models.I have given a corpus comprising of text from Harry Potter books. I am required to do the following:

1.Clean the data, this step can be done as per your choice. For example, you can remove
capitalizations, remove certain tokens or punctuations as per your requirement. 
2. Build N-gram models for n=1, 2, ... m, choose m suitably, whatever is appropriate according to your analysis. Show one sentence for each case.
3. Experiment with various smoothening methods (Add-One, Good-Turing, Kneser-Ney, Backoff, Interpolation) and report your results. 
4. Calculate perplexity for each case, report any trends or observations. You need to implement N-gram models, smoothening and perplexity functions from scratch, no libraries are allowed for these, libraries can be used for data cleaning. You need to report the best model by changing n values and smoothening. bold text** bold textbold text**

The purpose of this code is to calculate the perplexity of a language model using four different methods: Add-One smoothing, Good-Turing smoothing, Kneser-Ney smoothing, and Backoff smoothing.

Perplexity is a measure of how well a language model predicts a given set of observations. It is defined as the exponential of the average log-likelihood of the observations. The lower the perplexity, the better the language model is at predicting the observations.

Add-One smoothing is a method for estimating the probability of a word in a language model by adding 1 to the count of each word. This method is used to avoid zero probabilities, which can cause issues with some calculations.

Good-Turing smoothing is a method for estimating the probability of a word in a language model based on the number of occurrences of that word in the training data. It is used to estimate the probability of words that were not seen in the training data.

Kneser-Ney smoothing is a method for estimating the probability of a word in a language model based on the context in which the word appears. It is used to estimate the probability of words that were not seen in the training data.

Backoff smoothing is a method for estimating the probability of a word in a language model based on the context in which the word appears. It is used to estimate the probability of words that were not seen in the training data, and it takes into account the probability of lower-order n-grams when estimating the probability of higher-order n-grams.

The results of the code are the perplexities of the language model for each of the four smoothing methods. In this case, the Kneser-Ney and Good-Turing methods have the lowest perplexity, which means that they give the best predictions for the observations.bold text
