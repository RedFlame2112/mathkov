# mathkov
NLP for writing math problems

Natural Language Processor that analyzes a bank of past math problems and uses both spaCy and Markovify. 
I took a list of all the past AIME problems, then I proceeded to literally splice them together while taking out latex delimiters and commands so that the chain can analyze pure text.

From there, spaCy and Markovify handles the rest.
