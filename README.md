# Big-Scale Analytics
This is the repository of group Omega for the BSA project. We will upload further documentation in the future.

## Milestone 1
### Literature Review, Methodology

For the project we had searched for some paper with the key words like “foreign language” “level” and “machine learning”. 

In one of the paper (1) published on the  web site “Medium”, there were aslo links to the algorithmes like “BLEU” and “The Flesch–Kincaid readability tests ”. These are also explained in the wikipedia pages. 

The wikipedia page on ““The Flesch–Kincaid readability tests”   make use of the number of sylables in the sentences. It seems they take into consideration the #total sylabes,  #total words, and #total sentences.Flesch reading ease decreases with dificullty level, while the Flesch-Kincaid increases with difficulty.  Looking  some scores for Flesch reading ease test about  the daily used text materials like newspaper “Daily Digest” (score of 65), “Harward Law Review” (score of 30) , we can conclude about their precision as far as the level of these mentioned materials are concerned. As the score increases readibility level increases, i.e it becomes more easier to read.


In the paper (1), the author talks about legibility, which basically deals with format styles like bold or italic to make it easier for reading and understanding. Indeed, such format styles can help better understand. We thought other marks can also help reader understand better. For example a dialog which is represented inside quotation marks can be annotated for lower levels. This kind of approach makes use of styling elements. We will try to research into methodologies how styling elements can be incorporated into the machinelearning and prediction. Sylabe count is one of the central element of readibility assesments like “The Flesch–Kincaid readability tests”. For example, a dataset of words by sylabes is located over this site (3).

BLEU-bilingual evaluation understudy-is a method thar create measures based on comparison between machine translation and human translation.The wikipedia page on “BLEU” (4) and the other papar mentioned in the bibliography is a good source on the topic. This metrics is based on “corpus-based comprhensive and diagnostic evaluation”, “n-gram cooccurrence statistics”, “skip-bigram statistics”.

Machine evaluation techniques can be used to infill cloze test (texts with empty places to be filled). We understand this is not restricted to guessing a right answer, but also providing suggestions for alternatives (5).

We realized most of the text, translation, or word processing material in is located in "Linguistic-Language Processing" section of the University Library. Also, we noted that mostly the research in this domain contains many linguistics terms rather than programming codes or algorithmes. This gave us the first impression that this domain is more related to studies of letter as well as the data processing and data mining tools. 

We have revised the  libraries from our previous course, "Data Minning and Machine Learning".  The spacy libarary provides toolls to tokenize textes into words, sentences, their part of speach(POS).  CountVectorizer class of scikit learn enables us count the words in sentences in the corpus (6). 




### Sources

1-https://medium.com/glose-team/how-to-evaluate-text-readability-with-nlp-9c04bd3f46a2
2- Flesch–Kincaid readability tests
https://en.wikipedia.org/wiki/Flesch%E2%80%93Kincaid_readability_tests#Flesch%E2%80%93Kincaid_grade_level

3-Sylabes Counts:
http://countwordsworth.com/download/DaleChallEasyWordList.txt

4-Bilingual Evaluation Understudy  (BLEU)
https://en.wikipedia.org/wiki/BLEU

5-Cloze Test
https://en.wikipedia.org/wiki/Cloze_test

6-https://scikit-learn.org/stable/modules/generated/sklearn.feature_extraction.text.CountVectorizer.html

