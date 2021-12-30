# Fairy Tales Text Analysis
Text mining and sentiment analysis of adjectives and verbs that surround masculine (he/him/his) and feminine (she/her/hers) pronouns.

## How to start the analysis
1. Download and open folder on RStudio
2. run all code on an R notebook

## Project Overview
- Produced a text mining algorithm to compare the significance of words surrounding pronouns via analysis on R using the `tidytext` package. 
- Sentiment value was extracted from the verbs and adjectives surrounding feminine and masculine pronouns using `AFINN` lexicon. 
- The frequency and the sentiment of a word was then used to calculate sentiment severity.
- The word comparison between gender pronouns were then visualized for facilitated analysis using `ggplot2` package.
- The results demonstrate the stereotypical implication of genders roles within fictional plots. 

## Bigram Visualizations

### Initial Bigram (sample)
![alt_text](https://github.com/lylybell12/FairyTalesAnalysis/blob/main/visualizations/InitialBigram.PNG)

### Pronoun Separation Bigram (sample)
![alt_text](https://github.com/lylybell12/FairyTalesAnalysis/blob/main/visualizations/IntermediateBigram.PNG)

### Dimentionality Reduction Bigram (sample)
![alt_text](https://github.com/lylybell12/FairyTalesAnalysis/blob/main/visualizations/ReductionBigram.PNG)

## Bargraphs Comparing Sentiment Severity

### Sentiment Seversity for Masculine-associated words
![alt_text](https://github.com/lylybell12/FairyTalesAnalysis/blob/main/visualizations/SSM.png)

### Sentiment Seversity for Feminine-associated words
![alt_text](https://github.com/lylybell12/FairyTalesAnalysis/blob/main/visualizations/SSF.png)
