## Content Based Movie Recommendation System

- This model is built to recommend top five movies to the user with respect to their choice.
- It uses attributes such as genre, director, description, actors, etc. for movies, to make suggestions for the users. The intuition behind this sort of recommendation system is that if a user liked a particular movie or show, he/she might like a movie or a show similar to it.



## Model Description
**1.** This model is build to recommend movies on the content basis. <br>

**2.** Dataset is preprocessed and cleaned in python, pandas library is used to read the data in python, and import data in data frame format. <br>

**3.** Shape, info and null values are checked of both data frames. <br>

**4.** Datasets used in this project have two data frames, specific attributes are chosen from both data frames which help in recommendation of movies like title,genres etc. By joining those attributes tags are created.<br>

**5. PorterStemmer** : The Porter Stemming algorithm (or Porter Stemmer) is used to remove the suffixes from an English word and obtain its stem which becomes very useful in the field of Information Retrieval (IR). This process reduces the number of terms kept by an IR system which will be advantageous both in terms of space and time complexity.<br>
Porter stemmer is used in this model to choose words with similar root and give them same meaning. <br>

**6. CountVectorizer** : It is a great tool provided by the scikit-learn library in Python. It is used to transform a given text into a vector on the basis of the frequency (count) of each word that occurs in the entire text. This is helpful when we have multiple such texts, and we wish to convert each word in each text into vectors. <br>
Countvectorizer is used in this model to convert text into a vector on the count of frequency of each word.

**7. cosine similarity** : It measures the similarity between two vectors of an inner product space. It is measured by the cosine of the angle between two vectors and determines whether two vectors are pointing in roughly the same direction. It is often used to measure document similarity in text analysis. <br>
Cosine similarity is use in this model to find the similarities between movies.

**8. Movie recommendation function** : A function is designed inside model which which recommend the user top 5 similar movie according to their choice based on tags which are created earlier.

**9. Pickle** Python pickle module is used for serializing and de-serializing a Python object structure. Any object in Python can be pickled so that it can be saved on disk. What pickle does is that it “serializes” the object first before writing it to file. Pickling is a way to convert a python object (list, dict, etc.) into a character stream. The idea is that this character stream contains all the information necessary to reconstruct the object in another python script. <br>
Pickle library is used in this model to store data inside pickle and take it to user interface building in pycharm.

## Streamlit
- I have developed an user interface for Movie Recommendation by using streamlit.

  
![image](https://github.com/RahulSurenderSingh/Movie-Recommended-System-Content-Based/assets/136818857/9e8a85c6-7050-41b8-b958-d4b6ea6d3522)


# DATASET
- Download movies dataset from here
- https://www.kaggle.com/datasets/tmdb/tmdb-movie-metadata?resource=download


 

