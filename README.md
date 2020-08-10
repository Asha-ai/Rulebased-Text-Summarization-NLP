# Rulebased-Text-Summarization function-NLP 
## Auto text summarization
Automatic text summarization is the data science problem of creating a short, accurate, and fluent summary from a longer document.
Summarization methods are greatly needed to consume the ever-growing amount of text data available online. In essence, summarization is meant to help us consume relevant information faster.Text summarization is the problem of creating a short, accurate, and fluent summary of a longer text document.

Automatic text summarization methods are greatly needed to address the ever-growing amount of text data available online to both better help discover 
relevant information and to consume relevant information faster.
here for rule based text summarization using NLTK for munging texttokenization,
stopword removal etc
# Advantages of text summarization
Text Summarisation can be used to enable humans to quickly digest the content of large volumes of documents without the need to fully read them. 
An example of this is news feeds or scientific publications where there is a large volume of documents being constantly generated.
steps:
Find most important words
Compute a significance score for sentences based on words they contain
pick the top most significant sentences
# Word Importance
Generally few words are repeated in nature while writing a lession/document/text/story/news etc
so, word importance = word frequency
find most important words and compute the significance score for sentences based on words they contain
pick the top most significant sentences
# Sentence Significance
Sentences which encapsulate more of the
important words are more significant
Significance Score = Sum(Word Importance)
Major steps include
# 1) Extract text - Extract text to summarize
# 2) Preprocess Text 
- Tokenize text into sentences, 
-Tokenize sentences into words
-Remove stopwords
# 3) Extract Sentences 
- Compute frequencies of words
- Compute significance scores of sentences
- Rank sentences by their score
- Pick top N sentences

