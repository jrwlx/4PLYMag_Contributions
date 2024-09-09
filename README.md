# 4PLYMAG 
# http://4plymag.com/yuto/
# http://4plymag.com/yutodunks/

Code and Datasets used for 4PLY

Thank you Pete for making this happen!

And this project was heavily inspired by Jared Wilbur's (https://github.com/jwilber) breakdown of Eric Koston at http://4plymag.com/koston/

DATASETS

Collected manually through watching youtube videos.

There are some errors in the datasets such as:
- inconsistent trick naming (ex. noseslide vs nose)
- misspelled trick names
- trick names I did not know (ex. lots of transition tricks)
But were remedied to the best of my ability in the code.

Explanation of some columns: 
- line: line will have same number to indicate it was done in a line
- obstacle: flat, gap, rail, ledge, manual, transition were used just to simplify the data and make it easier to analyze/visualize
- stance: 0, 1, 2, 3 means regular, switch, fakie, nollie

For contest dataset, yutocontest.csv:
- obstacle column has another category of 'bank' which consist of tricks done into a bank, out of a bank, or bank to bank



CODE 

It's probably not the most optimized code, but I tried to my best to organize and make it easy to read. 

Used Pandas to preprocess and clean data
Used Matplotlib and Seaborn to visualize data 
