# Content-Based-Movie-Recommender-System

Content Based Recommender System recommends items similar to the items user likes. How does it decide which item is most similar to the item user likes? Here we use the similarity scores.

## Similarity Score : 
   It is a numerical value ranges between zero to one which helps to determine how much two items are similar to each other on a scale of zero to one. This similarity score is obtained measuring the similarity between the text details of both of the items. So, similarity score is the measure of similarity between given text details of two items. This can be done by cosine-similarity.
   
## How Cosine Similarity works?
  Cosine similarity is a metric used to measure how similar the documents are irrespective of their size. Mathematically, it measures the cosine of the angle between two vectors projected in a multi-dimensional space. The cosine similarity is advantageous because even if the two similar documents are far apart by the Euclidean distance (due to the size of the document), chances are they may still be oriented closer together. The smaller the angle, higher the cosine similarity.
  
More about Cosine Similarity : [Understading Math behind Cosine Similarity](https://www.machinelearningplus.com/nlp/cosine-similarity/)


This is a hollywood movie recommender system built with Python. I've used IMDB 5000 Movie Dataset to built this.

Live Demo : [Movie Recommender System by Kishan](https://movierecommendersystem.herokuapp.com)

Link to the dataset :- [IMDB 5000 Movie Dataset](https://www.kaggle.com/carolzhangdc/imdb-5000-movie-dataset)


