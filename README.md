# Deception-Fake News Dection

## What is Fake News?
Fake news is false or misleading information presented as news

## What is a TfidfVectorizer?
TF(Term Frequency): the number of times a word appears in a documment it is the Term Frequency. A higher value means a term appears more often than others, and so the document is a good match when the term is part of search terms.

IDF(INverse Document Frequency): Words that occur many times a document,but also occur many times in many others,may be irrelevant. IDF is a measure of how significant a term is in the entire corpus.
The TfidfVectorizer converts a collection of raw document inot a matrix of TF-IDF features.

## What is a PassiveAggresiveClassifier?
Passive Aggressive algorithms are online learning algorithms. Such an algorithm remains passive for a correct classification outcome, and turns aggressive in the event of miscalculation, updating and adjusting. Unlike most other algorithms, it does not coverage. Its purpose is to make updates that correct the loss, causing very little change int the norm of the weight vector.

## Summary
We took a political dataset, implemented a TfidfVectorizer, initialized a PassiveAggressiveClassifier, and fit our model. We obtaining an accuracy of 92.82% in magnitude.
