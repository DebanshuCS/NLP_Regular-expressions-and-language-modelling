
# Regular expressions and language Modelling, NLP

## Regular expressions

Download some example books from “Project Gutenberg” that are included Link.
E.g, https://www.gutenberg.org/files/1342/1342-h/1342-h.htm

You copy some plain texts and save in a .txt files.
This exercise is open ended. Use your favourite programming language, or the Unix grep utility,
or the following two utility programs, regexs.py and regexcount.py, to explore this corpus. 

If you
use the python code, use required libraries to write programs such as to search the text file for
words over 10 characters long. Note the use of quotes to ensure that the spaces are interpreted as
part of the regular expression.

Find some interesting patterns, and write up the regexes that describe those patterns, some
example results, and an explanation for why they're interesting. Some examples include (1)
common morphological suffixes, (2) patterns that indicate proper names, (3) patterns that indicate
verbs, etc. Tokenize the text file and mention the counts of top 10 words excluding stop words. 

## Language Modelling

Language modeling involves developing a statistical model for predicting the next word in a
sentence or next letter in a word given whatever has come before. It is a pre-cursor task in tasks
like speech recognition and machine translation.

Use the source below as the beginner language modeling datasets.
Project Gutenberg, a large collection of free books that can be retrieved in plain text for a
variety of languages.

**Task: Build a language model/ n-gram (Unigram, bigram, and trigram).**

Step-1: Build a text corpus using any one or two of the English books given in the above link
(https://www.gutenberg.org/). These books (text versions) will be used as text corpus. You
compile one or more books according to their genre into a single text corpus.

Step-2: Write a program to count the word frequencies (unigram), bigram, and trigram.

Step -3: Prepare a bigram probability table showing probabilities of some frequent bigrams. You
can also do Add-1 smoothing. Using these probabilities, calculate probabilities of some sentences
(taking from the corpus and outside).

Step-4: Using the above bigram and trigram probability models that you prepare, predict the next
word (top 5 probable) given the previous n-gram for the sentence below.
Sent – to be ??? (Predict the next words after “to be”) 