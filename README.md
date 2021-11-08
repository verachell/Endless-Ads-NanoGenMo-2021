# Endless-Ads-NanoGenMo-2021
Generates a series of fictional advertisements of > 50,000 words. The solution in the first ad becomes the problem in the second ad, and so on.

## Endless Ads - a solution for every problem, and a problem for every solution
### Usage - how to run this program
Please note: This code requires that:   
- ```ruby``` is installed on your machine and  
- you have the ```yeetwords.rb``` file from the YeetWords repository (see below for where to place it).  

To run this ad generator, first download the contents of this repository into your working directory. You will also need to download the ```yeetwords.rb``` file from the [YeetWords repository](https://github.com/verachell/YeetWords) (I used v 1.1.3 but any version 1.1.0 and above should work) and place it at the same directory as ```ads.txt``` from this repository.

Then in your command line, type ```ruby yeetwords.rb ads.txt```

A file of fictional advertisements of > 50,000 words in markdown format will be generated. The solution in the first ad becomes the problem in the second ad, and so on. You will not prompted for anything except for the output filename if a file with the default name already exists.

### Credits - sources of words and sentences
#### Words
- Adjectives, nouns, infinitive verbs and conjunctions were from https://github.com/verachell/English-word-lists-parts-of-speech-approximate  

- Negative adjectives, positive adjectives, large nouns and portable nouns were from https://github.com/verachell/English-word-lists-miscellaneous-categories  

- Latin suffixes that I used here to create company names were from https://en.wiktionary.org/wiki/Category:Latin_noun-forming_suffixes  

- Male and female names came from the list of most popular baby names in the US for the year 2019 at https://www.ssa.gov/OACT/babynames/index.html. The 200 most popular names for male and for female names were used in this project.

- The other word lists I just made up myself, often with help from the thesaurus https://www.freethesaurus.com/

#### Sentences

- I generated my own sentence templates
