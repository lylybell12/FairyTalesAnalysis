# Fairy Tales Text Analysis (first semester progress)
Text mining and sentiment analysis of adjectives and verbs that surround masculine (he/him/his/himself) and feminine (she/her/hers/herself) pronouns. The goal is to use this text-mining algorithm to assess the effects of sexism in children's educational content to uncover underlying influences in gender and STEM enrollment disproportionality. 

## How to start the analysis
1. Download and open folder on RStudio
2. Run all code on an R notebook

## Project Overview
- Produced a text mining algorithm to compare the significance of words surrounding pronouns via analysis on R using the `tidytext` package. 
- Sentiment value was extracted from the verbs and adjectives surrounding feminine and masculine pronouns using `AFINN` lexicon. 
- Sentiment severity was calculated using the frequency and the sentiment value of a word. 
- The word comparison between gender pronouns were then visualized for facilitated analysis using `ggplot2` package.
- The results demonstrate stereotypical implications of gender roles within fictional plots. 

## Assumptions
- Although gender is non-binary we only considered male and female pronouns for
simplicity and ignored neutral pronouns such as ‘they/them.’
- Proper nouns such as ‘John’ or ‘Jane’ were not considered.
- Dataset contained only top 20 popular fairy tales.


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
