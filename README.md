# NLP

## Sentiment Analysis
1. Read in newsapi key and set a newsapi client. 
2. Fetch articles about Bitcoin and Ethereum.
3. Create sentiment scores dataframes using a for loop. One for bitcoin, and the other for ethereum. Then describe the respective sentiment score dataframes. 

## Tokenizer
1. Using nltk, establish WordNetLemmatizer to a variable. 
2. Define a tokenizer function that sets stopwords, takes out punctuation, turns everything lower case, tokenizes each word, and lemmatizes the words so they no longer have gramatical differentiators. 
3. Create a new column in the respective coin dataframes for the tokenized text. 

## NGrams and Frequency Analysis 
1. Cluster words into n-grams, phonemes, syllabels, letters, words, or base pairs, and pull the 10 most common pairings. 
2. Pull top 10 individual words from both bitcoin and ethereum articles.

## Word Clouds
1. Create word clouds to display the most commonly used words in the Bitcoin and Ethereum articles respectively. 

## Name Entity Recognition
1. Using the respective coin dataframes separately, concatenate the text. 
2. With the stand alone text now as a variable, use displacy to visualize the entities within the articles. List those entities as text, then label. 
