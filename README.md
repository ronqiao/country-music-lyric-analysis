Ron Qiao  
May 2019  

# __Country Music Lyric Analysis__
#### Analyzing song lyrics with natural language processing and Non-negative Matrix Factorization (NMF) / Correlation Explanation (CorEx) topic models  
<hr>  
This project explores Country music as a genre by extracting and analyzing lyrics from songs posted on Billboard's weekly hot 50 charts. Topic modeling, though not an exhaustive approach, proves useful in exploring music genres by allowing users to discover previously hidden themes and motifs in song lyrics. Introducing a time series element to the dataset also allows users to visualize trends in topic distributions over several decades.     

In this case, the models and visualizations demonstrate how country music can in fact, be quite relatable; namely, that its lyrics represent a lot more than just beer, trucks, and women (themes commonly present in modern day bro-country). Applying CorEx / word anchors in a semi-supervised learning manner also reveals some more interesting, esoteric topics in Country music.  

The project can be broken down into the following steps:  

#### 1. Data Acquisition  
\- 1a. Scrape Billboard chart archives and populate corpus of country songs  
\- 1b. Scrape lyrics for each song from WikiLyrics and Genius APIs
#### 2. Preprocessing - Lyrics / Data  
\- 2a. Use natural language processing and other methods to process text lyrics and data. Introduce some EDA and basic feature engineering     
#### 3. Models / Analysis  
\- 3a. Apply non-negative matrix factorzation and CorEx to model topics and then analyze the results  

