# NLP_2026_A2



2.2

Step 2

One main reason of all large language models is to predict the upcoming word based on the current sequence. Mathematically, it is to compute the conditional probability of a word given its entire history. However, the language is quite creative, and, to express the same thing, there are many sentences with variant lexical and grammatical forms. Thus, it is difficult to get an accurate probability of a next word, especially when given a long sequence of 10 or 20 words. Based on Markov assumption, where the probability of a word depends only the previous one, n-gram model is computing that probability by approximating that long history by the last few words.  