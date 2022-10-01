# Predicting-Text-Readability
The simple Wikipedia was created to address the need for a simplified source of information accessible to individuals with learning disabilities, low reading proficiency, and new English learners. Though the assumption is that the language contained within it is simple enough, finding areas where the language requires further simplification is worth exploring. Before the editors expend resources on increase its readability, it would be very helpful to provide suggestion on which parts of an article's text might need to be simplified.

The goal of this project is to classify documents (where each document is a line in the data file), into one of two categories **0** for when the sentence does NOT need to be simplified and **1** for when the sentence DOES need to be simplified.

There are several aspects of a text that influence its readability, including the vocabulary level, the syntactic structure, and overall coherence. When deciding on the features to be extracted we decided on the following:

1. Surface Features
    * Average number of characters per word in the document.
    * Average number of words per sentence in the document.
    * Total number of words in the document
    
2. Syntactic Features
    * Number of noun phrases in the document
    * Number of verb phrases in the document
    
3. Discourse and coherence features
    * Number of pronouns in the document
    * Number of coordinate and subordinate conjuncts in the document
    
4. Readability scores
    * Age of Acquisition (the approximate age in years when a word was learned)
    * Flesch Reading Ease Score (low scores indicate higher difficulty)
    * Dale-Chall Readability Score (uses a lookup table of the most commonly used 3000 English words and returns the grade level  using the New Dale-Chall Formula)
    * McAlpine EFLAW Readability Score (Returns a score for the readability of an english text for a foreign learner or English, focusing on the number of miniwords and length of sentences)



