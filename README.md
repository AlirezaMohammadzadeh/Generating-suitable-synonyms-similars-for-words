# Generating-suitable-synonyms-similars-for-words

It happends for us so many times that we have searched a wrong word but we got to the result
that we could reached if we searched correct form of the word
,but how can search engine findout what did really we want?

It called synonym similar algorithm that uses textmining tools for finding suitable synonyms
and similars for words.  
In this program I used nlp tools for generating suitable synonyms and similars for our product's names that we read them
from an excel file(Input_words.xlsx) and after generating the synonyms and similars insert them into excel file
(synonyms_similars.xlsx)  

I used gensim  python library for generating synonyms and similars for our English words.  
This library uses Word2Vec technique for natural language processing.  
This technique helps us finding synonyms and similars for words.   
You can read more about this techniques in:[Word2Vec](https://en.wikipedia.org/wiki/Word2vec)     
You can get some information about this nlp librarary in:[Gensim](https://en.wikipedia.org/wiki/Gensim)    

I used api.text-mining.ir for generating synonyms and similars for our Persian words.  
text-mining.ir provides some nlp tools for processing Persian text.  
You can read more about it in:[text-mining.ir](https://text-mining.ir/)  
I used itertools,Levenshtein for measuring orthographic similarity between two words.  
You can read about itertools:[itertools](https://docs.python.org/3/library/itertools.html)  
and also you can read about Levenshtein:[Levenshtein](https://pypi.org/project/python-Levenshtein/)  
I used spaCy for tokenizing product names.   
about [spaCy](en.wikipedia.org/wiki/SpaCy)  
Tokenization is used in natural language processing to split paragraphs
and sentences into smaller units that can be more easily assigned meaning.
The first step of the NLP process is gathering the data (a sentence) and
breaking it into understandable parts (words)
