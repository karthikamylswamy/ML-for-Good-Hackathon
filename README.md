
# ML For Good with Child Mind Institute Data

## Team 29

## Developers:
Ali Lotfdar  
Anju Jain  
Karthika Mylswamy   
Venkatesh Taduvayi   

# Project Overview:

In this project we have done the following use cases

1. Crislogger: Sentiment analysis and topic modeling with crisis logger data using various methodologies
2. ProlificAcademy: Finding the Polarity and subjectivity of the positive statements and the correlation between the positive change with the various activities like social media, isolated, video game, outdoor. Along with the positive/negative impact based on occupation, worry and other features.

The first use case can be found in the notebook: team29_CrisisLogger.ipynb      
The second use case can be found in the notebook: team29_ProlificAcademic.ipynb    

# Use case 1: Crisis Logger
The crisislogger data had the transcriptions and with that data we have done the sentiment analysis and topic modeling.

We have showcased the sentiments like positive, negative and neutral using various NLP model/ algorithm We also did the word cloud to highlight the most frequently used words. 

### Feature used:
transcriptions 

### Methodology:
textblob   
SentiWordNet   
Vader   
Spacy 
LDA Model 

# Use case 2: ProlificAcademy

In this use case we have done the following

1. showcased the polarity and subjectivity based on the feature specifypositive (free text field)
2. Showcased the positive or negative correlation between the feature positivechange and activities features like social media, isolated, video game, outdoor
3. Analyzed the positive/negative/neutral impact based on the occupation and worry.
4. Created a heatmap to show the correlation between the worry and features like positivechange, country, infected, sex, education, mentalhealth, financedifficulty, livingdifficulty, foodsecurity


### Features used:
specifypositive  
positivechange    
priorsocialmedia  
isolated   
priorvideogames   
outdoorsprior  
socialmedia   
isolated  
videogames  
outdoors  
priorvideogames_2  
outdoorsprior_2  

occupation  
priorworry  
worriedyourself  

country   
infected  
sex  
education  
mentalhealth  
financedifficulty  
livingdifficulty   
foodsecurity  

### Methedology:
Data cleaning  
Data Normalization   
Sentiment Analysis  
Correlation Analysis  
Longitudinal analysis  
Linear regression   




# Packages and Models used in both use cases:
sklearn   
nltk   
panda  

wordcloud  
textblob   
spacytextblob   

matplotlib   
seaborn 
plotpy   

Image   
vaderSentiment   
SentiWordNet   
spacy   
en_core_web_sm    
gensim   
pyLDAvis.gensim   
pyLDAvis   

Linear Regression    













