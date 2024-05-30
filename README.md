
------------------------------------------------------------------------------------------
# Content-Based-Movie-Recommender-System-with-sentiment-analysis

Content Based Recommender System recommends movies similar to the movie user likes and analyses the sentiments on the reviews given by the user for that movie.


## Similarity Score : 

   How does it decide which item is most similar to the item user likes? Here we use the similarity scores.
   
   It is a numerical value ranges between zero to one which helps to determine how much two items are similar to each other on a scale of zero to one. This similarity score is obtained measuring the similarity between the text details of both of the items. So, similarity score is the measure of similarity between given text details of two items. This can be done by cosine-similarity.
   
## How Cosine Similarity works?
  Cosine similarity is a metric used to measure how similar the documents are irrespective of their size. Mathematically, it measures the cosine of the angle between two vectors projected in a multi-dimensional space. The cosine similarity is advantageous because even if the two similar documents are far apart by the Euclidean distance (due to the size of the document), chances are they may still be oriented closer together. The smaller the angle, higher the cosine similarity.
  
  ![image](https://user-images.githubusercontent.com/36665975/70401457-a7530680-1a55-11ea-9158-97d4e8515ca4.png)

  
More about Cosine Similarity : [Understanding the Math behind Cosine Similarity](https://www.machinelearningplus.com/nlp/cosine-similarity/)

### Sources of the datasets 

1. [IMDB 5000 Movie Dataset](https://www.kaggle.com/carolzhangdc/imdb-5000-movie-dataset)
2. [The Movies Dataset](https://www.kaggle.com/rounakbanik/the-movies-dataset)
3. [List of movies in 2018](https://en.wikipedia.org/wiki/List_of_American_films_of_2018)
4. [List of movies in 2019](https://en.wikipedia.org/wiki/List_of_American_films_of_2019)
5. [List of movies in 2020](https://en.wikipedia.org/wiki/List_of_American_films_of_2020)

--------------------------------------
pip install Flask==1.1.1
pip install gunicorn==19.9.0
pip install Jinja2==2.11.3
pip install MarkupSafe==1.1.1
pip install Werkzeug==0.15.5
pip install numpy>=1.9.2
pip install scipy>=0.15.1
pip install nltk==3.5
pip install scikit-learn>=0.18
pip install pandas>=0.19
pip install beautifulsoup4==4.9.1
pip install jsonschema==3.2.0
pip install tmdbv3api==1.6.1
pip install lxml==4.6.3
pip install urllib3==1.26.5
pip install requests==2.23.0
pip install pickleshare==0.7.5

