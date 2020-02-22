# spotify-analysis
- Sentiment Analysis on Bob Dylan's music to see how his music changed over time: whether it has become more positive, negative or stayed the same. 
- This code does the following: 
Calls APIs, connects to data sources, data wrangling, and Text Analysis (using NLTK package).
- Final tables are generated in the end, which can be dowmloaded in any format using pandas package, this code shows downloading final tables as a csv (last line of python program):
# write this sentiment analysis data set to csv for creating visualization in tableau
new_grouped_data.to_csv('~/Case_Studies/Spotify_Senti_Analysis.csv')
- This new data set creates visualizations in tableau for a better interactive dashboard experience. 