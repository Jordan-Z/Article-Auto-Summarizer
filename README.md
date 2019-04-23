# wm-project-final-Jordan-Z

Objective - create a summarizer that makes a summary from any article on the web.
 
Question - Is an article's title really a good representation of the article?

Create a summary using clustering. Creates an automated summary of an article by finding how often words are used in each sentence.
 Using those most commonly used words, score each sentence in the article and build a summary of the article based off sentence score. 
The sentences are scored by how close the most common words are to each other in the sentence.  

Create a summary using the title of the article as the phrase passed in as the important words. 

Compare the summarys to see if they are similiar.

Hypothesis - The summary that was generated based off most commonly used words and how closely those words are in each sentence should be 
a better representation of the article. 





Python modules:
Pickle, 
requests, 
BeautifulSoup, 
nltk, 
re, 
numpy,
difflib
