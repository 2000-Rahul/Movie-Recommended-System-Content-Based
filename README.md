# Content Based Movie Recommendation System

- It uses attributes such as genre, director, description, actors, etc. for movies, to make suggestions for the users. The intuition behind this sort of recommendation system is that if a user liked a particular movie or show, he/she might like a movie or a show similar to it.



# Description
- This model is build to recommend movies on the content basis.
- Dataset is preprocessed and cleaned in python.
- Datasets used in this project have two tables, specific attributes are chosen from both datasets which help in recommendation of movies like title,genres etc. By joining those attributes tags are created.
- **PorterStemmer** The Porter Stemming algorithm (or Porter Stemmer) is used to remove the suffixes from an English word and obtain its stem which becomes very useful in the field of Information Retrieval (IR). This process reduces the number of terms kept by an IR system which will be advantageous both in terms of space and time complexity.
- **CountVectorizer** It is a great tool provided by the scikit-learn library in Python. It is used to transform a given text into a vector on the basis of the frequency (count) of each word that occurs in the entire text. This is helpful when we have multiple such texts, and we wish to convert each word in each text into vectors.
- **cosine similarity** It measures the similarity between two vectors of an inner product space. It is measured by the cosine of the angle between two vectors and determines whether two vectors are pointing in roughly the same direction. It is often used to measure document similarity in text analysis.
- **Pickle** Python pickle module is used for serializing and de-serializing a Python object structure. Any object in Python can be pickled so that it can be saved on disk. What pickle does is that it “serializes” the object first before writing it to file. Pickling is a way to convert a python object (list, dict, etc.) into a character stream. The idea is that this character stream contains all the information necessary to reconstruct the object in another python script.

# Streamlit
- I have developed an user interface for Movie Recommendation by using streamlit.

  
![image](https://github.com/RahulSurenderSingh/Movie-Recommended-System-Content-Based/assets/136818857/9e8a85c6-7050-41b8-b958-d4b6ea6d3522)


# DATASET
- Download dataset from here
- https://www.kaggle.com/datasets/tmdb/tmdb-movie-metadata?resource=download

