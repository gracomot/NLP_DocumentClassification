# NLP_DocumentClassification
A program that makes use of supervised learning classifiers in the Natural Language Toolkit (NLTK). The program takes as input 181 State of the Union addresses (92 by Republican and 89 by Democratic U.S. Presidents), and uses a ***bag-of-words*** approach to extract features and classify each speech as either being made by a Republican or Democratic President.

### Input
* ***sotu.txt***: contains the text of 233 State of the Union speeches (including those from Presidents who were neither Republicans or Democrats – these are excluded and not processed).The data was gathered from multiple sources (and thus formats), and some speeches are spread across multiple lines of text. 

### Processing
The following steps are applied;
* Things to consider
  * whether or not to remove punctuation like periods, commas, colons, semi-colons, question marks, exclamation points, double quotes, etc
  * whether to remove stopwords (NLTK stopwords may be augmented by others you believe appropriate for removal)
  * whether to normalize text to lowercase
* Features are extracted from the bag-of-words that are helpful in classifying the speeches. Common bag-of-word features are: counts of (certain) words; presence of (certain) words; (average) length of words; (average) length of sentences; (average) length of (entire) text, etc.

### Output
The program is run 30 times and the results averaged. Only the final averaged results
   for overall classifier accuracy; and for precision, recall, and F1 measures on a per-class basis are reported.

