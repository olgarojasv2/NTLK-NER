# Natural Language Processing 

This project contains a series of NLP tasks performed on a collection of texts, including translations of Tom Sawyer by Mark Twain. The analysis is conducted using NLTK and spaCy libraries in Python.

## Part I

1. Sentence splitting and word tokenization
   - Word frequency statistics
   - Plot of 25 most common words
2. Stemming using Porter and Lancaster stemmers
   - Comparison of stemmed and unstemmed results
4. POS-tagging on Tom Sawyer translations (nl-en-de)
   - Frequency report of POS tags.

## Part II

1. Named Entity Recognition (NER)
   - Manual annotation of 2 sentences per file -10 sentences in total-
   - Performance evaluation of automatic NER: Report, Precision, Recall, F1 Score.

### What is...? Key Concepts
## Named Entity Recognition (NER)
NER is a subtask of information extraction that seeks to locate and classify named entities in text into pre-defined categories such as names, organizations, places, etc. It's extremely useful for extracting structured information from unstructured text.

## Part-of-Speech (POS) Tagging
POS tagging is the process of assigning grammatical categories (e.g., noun, verb, adjective) to each word in a sentence. This helps in understanding the structure of sentences and meaning.

## Porter Stemmer
Porter Stemmer is a widely used stemming algorithm for English words. It employs a set of rules to remove or replace word endings, reducing inflected words to their word stem. It's not as aggressive as other stemmers and will provide a decent compromise between performance and readability.

## Lancaster Stemmer
The Lancaster Stemmer is one of the strongest stemming algorithms. It has a greater number of rules than Porter, and this leads to over-stemming in some cases. It produces shorter stems and is faster -great for large datasets-, but the resulting stems in some cases are not actual words.

## References
SpaCy: https://spacy.io/
Precision-Recall Score: https://stackoverflow.com/questions/55724707/how-to-calculate-precision-recall-score-for-keywords-in-sklearn-python
Scikit-learn: https://scikit-learn.org/stable/
