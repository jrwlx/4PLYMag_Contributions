# 4PLYMAG 
This repository contains code and datasets used for the analysis and visualization of two articles published for 4PLY Magazine. 

### http://4plymag.com/yuto/

### http://4plymag.com/yutodunks/

## Acknowledgments

Thank you Pete from 4PLY for helping guide the data, getting the articles live, and just being awesome. 
This project was heavily inspired by Jared Wilbur's breakdown of Eric Koston http://4plymag.com/koston/

## DATASETS

Collected manually through watching youtube video using google sheets. 

**yuto.csv** contains all tricks from 5 video parts 
1. Nike SB | Yuto Horigome | April Skateboards Pro Part - May 2019
2. The Yuto show ! - June 2021
3. Yuto Horigome's "Spitfire" Part - Dec 2021
4. Nike SB | Yuto Horigome in Tokyo - Aug 2023
5. Yuto Horigome's "April" Part - Dec 2023

**Explanation of some columns:**
- line: line will have same number to indicate it was done in a line
- obstacle: flat, gap, rail, ledge, manual, transition were used just to simplify the data and make it easier to analyze/visualize
- stance: 0, 1, 2, 3 means regular, switch, fakie, nollie

**Some errors in the datasets such as:**
- inconsistent trick naming (ex. noseslide vs nose)
- misspelled trick names
- trick names I did not know (ex. lots of transition tricks)
But were remedied to the best of my ability in the code.

**yutocontest.csv** 
- most major competitions starting with the XGames on June 1, 2019 up to Tampa Pro on April 7, 2024 (not exhaustive list) 
- contains only best scored 'runs' and 'best trick' from competitions where Yuto placed 3rd or higher 
- obstacle column has another category of 'bank' which consist of tricks done into a bank, out of a bank, or bank to bank

## CODE 

Code was executed in Jupyter Notebook and using libraries such as Pandas to preprocess and clean data, and Matplotlib and seaborn to visualize data. Not all visualizations present in the code were used in the final article. 

**yuto.ipynb** goes with http://4plymag.com/yuto/

**yutoshows.ipynb** goes with http://4plymag.com/yutodunks/
