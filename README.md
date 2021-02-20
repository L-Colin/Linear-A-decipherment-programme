# Linear-A-decipherment-programme
A Linear A decipherment programme written in Python language

This is a guide for users of the Linear A decipherment programme

##1. Overview 
The main window of our programme presents four key analysis functions 
   - General decipherment
   - LinAfontConv
   - Specific Decipherment
   - Analysis - I
This programme aims to to provide automated methods to evaluate languages which greatly resemble Linear A.

##2. Specific Decipherment
There are 9 built-in dictionaries for comparison with Linear A available in this function. These include Hamito-Semitic, Ancient Egyptian, Albanian, Luwian, Proto-Celtic, Anatolia, Basque (Both Pre-Basque and Proto-Basque), Hittite and Thracian.

-Interpreting Output
The output for each specific decipherment contains two tables. The first of which is a result of a consonantal comparison - vowels in the dictionaries were conditionally ignored to produce a one-to-one comparison between consonants. After performing said comparison, positive matches are displayed as shown.

Each entry is displayed in this order: the identical matches from the comparison, the original word in said dictionary, the Linear A word and the source from which the Linear A word was found. 
The second table is a result of frequency analysis. The matching consonants in each matching triplet were counted, and are represented by letters a-z.

For example, the triplet 100 matched with the letter 'd' once, but matched with none of 'a', 'b', 'c' and 'd'.

Under the percentage analysis function, it provides the statistical analysis of the matches between the Luwian dictionary as well as the transcribed Linear A sources (GORILA volumes 1 - 5 inclusive). The analysis involve the number of unique matches, the total number of matches as well as the percentage of matches.

##3. General Decipherment 
The General Decipherment function enables dynamic comparisons - users can supply their own Linear A list ("base sheet") and the dictionary list ("comparison sheet"). 

3.1 Formating Input

Base Sheet
The base sheet must be in the comma-separated values (.csv) format. 

The entries must be listed as shown, in the order of "Source", "NEW FORMAT" and "Linear A". The source column is the corresponding source of the Linear A word and the linear A column shows the representation of the Linear A word in the base sheet.

Comparison Sheet
The comparison sheet must be in the .csv format as well. 

The spreadsheet should contain only one column, which is represented as the "List" column as shown. The following entries are the words in the comparison dictionary.

3.2 Interpreting Output
This function also provides the output from a consonantal comparison, similar to that in Specific Decipherment.

Assuming this is a dynamic comparison between the Linear A base sheet and an unknown comparison sheet, we see that the consonant cluster "kns" has 6 identical matches with the corresponding Linear A words, the original word and its corresponding source. The original word refers to the corresponding word in the comparison sheet.




















