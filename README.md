# FuzzyWuzzy
This Jupyter notebook compares two lists using fuzzy matching and outputs the matches.

Dependencies: `pip install fuzzywuzzy`

Left the output so you could see a few things.
First, the error you may get if you don't have the proper library installed.
Second, how the names match and the score. In reality, you iterate a lot, pruning out the good matches, reducing your dataset
and then running the script again and again, manually checking to make sure you have correct matches. 

Painful but effective. 

One could say this is a fuzzy intersection betwixt two columns of data, in this case the data sources come from two different files. 

The value here is the comparison captures variants, misspellings and acronyms. 
