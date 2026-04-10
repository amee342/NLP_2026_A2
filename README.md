# NLP_2026_A2



2.2

Step 2

1. One main reason of all large language models is to predict the upcoming word based on the current sequence. Mathematically, it is to compute the conditional probability of a word given its entire history. However, the language is quite creative, and, to express the same thing, there are many sentences with variant lexical and grammatical forms. Thus, it is difficult to get an accurate probability of a next word, especially when given a long sequence of 10 or 20 words. Based on Markov assumption, where the probability of a word depends only the previous one, n-gram model is computing that probability by approximating that long history by the last few words.  

3. In addition to probability of a generated sequence, perflexity is another intrinsic metric to evaluate the performance of the language models in terms of word prediction task. The metric is defined as the inverse of the probability of any sequence normalized by the length of that sequence. By doing so, it is more fair to compare across texts with different length. The intuition of perplexity is that **the lower perplexity of a model, the better the model performs**. 


