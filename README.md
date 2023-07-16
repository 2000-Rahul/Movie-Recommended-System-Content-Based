## Content Based Movie Recommendation System

- This model is built to recommend top five movies to the user with respect to their choice.
- It uses attributes such as genre, director, description, actors, etc. for movies, to make suggestions for the users. The intuition behind this sort of recommendation system is that if a user liked a particular movie or show, he/she might like a movie or a show similar to it.



## Model Description
**1.** This model is build to recommend top five  movies on the basis of content with respect to user intrest. <br>

**2.** Jupyter Notebook is used in this model for implementation of coding.

**3.** Dataset is preprocessed and cleaned in python programming language, pandas library is used to read the data in python, and import data in data frame format. <br>

**4.** Datasets used in this project have two data frames, specific attributes like title,genres etc are chosen from both data frames which help in recommendation of movies to the user. By joining those attributes tags are created.<br>

**5.** NLP Deep Learning techniques like cosine similarity, CountVectorizer,Stemming are used in this project to make this project successfull and precise.<br>

**6.** To develop user interface Pycharm IDLE is used for python programming language and with help of streamlit library inside python user interface is developed.

## Model Building Steps

**1.Import libraries** <br>

 - Python libraries like pandas and numpy is imported inside jupyter notebook.

**2. Reading Data** <br>

- Data is read in the data frame format with the help of pandas library.
- Two different table are impoted inside jupyter notebook.
- pd.read_csv() function is used to read the data in data frame format.

**3. Data Preprocessing** <br>

- Both data frames are preprocessed and necessary attributes are selected from both data frames which will help in recommendation of movies.
- Single data frames is formed after merging important atrributes from both data frames.
- Null values are checked and droped from the dataset.
- changing format of attributes with the help of importing ast(Abstract Syntax Tree) inside python.
-  The ast.literal_eval method can safely evaluate strings containing Python values from unknown sources without us having to parse the values. However, complex expressions involving indexing or operators cannot be evaluated using this function.
-  By using ast.literal_eval function import Keywords are selected from attributes .
-  Transformation is applied on all attributes with the help of lambda function to remove space among words.

**4. Tags** <br>

- Tags are formed by joing attributes of data frame which will contribute in recommandation of movies.


**5. Stemming Process** <br>

The Porter Stemming algorithm (or Porter Stemmer) is used to remove the suffixes from an English word and obtain its stem which becomes very useful in the field of Information Retrieval (IR). This process reduces the number of terms kept by an IR system which will be advantageous both in terms of space and time complexity.<br>
Porter stemmer is used in this model to choose words with similar root and give them same meaning. <br>

**6. Text Vectorization**

- Import CountVectorizer from sklearn to perform text vectorization.

- Text Vectorization - It is the process of converting text into numerical representation.


- CountVectorizer : It is a great tool provided by the scikit-learn library in Python. It is used to transform a given text into a vector on the basis of the frequency (count) of each word that occurs in the entire text. This is helpful when we have multiple such texts, and we wish to convert each word in each text into vectors. <br>
Countvectorizer is used in this model to convert text into a vector on the count of frequency of each word.

**7. cosine similarity** 
- It measures the similarity between two vectors of an inner product space. It is measured by the cosine of the angle between two vectors and determines whether two vectors are    pointing in roughly the same direction. It is often used to measure document similarity in text analysis. <br>
- cosine distance is between 0 and 1.
- if cosine angel is small, movie are similar.
- Cosine similarity is use in this model to find the similarities between movies.

**8. Movie recommendation function** 
- A function is designed inside model which which recommend the user top 5 similar movie according to their choice based on tags which are created earlier and by using NLP Deep Learning techniques like cosine similarity. Movies which have top 5 cosine similarity according to user choice are recommended to the user.

**9. Evaluating model**
- Model is evaluated by calling the movie recommedation functaion and output shown is precise and accurate.

## USER INTERFACE

**Pickle**

- Python pickle module is used for serializing and de-serializing a Python object structure. Any object in Python can be pickled so that it can be saved on disk. What pickle does is that it “serializes” the object first before writing it to file. Pickling is a way to convert a python object (list, dict, etc.) into a character stream. The idea is that this character stream contains all the information necessary to reconstruct the object in another python script. <br>

- Pickle library is used in this model to store data inside pickle and take it to user interface building in pycharm.

 **Streamlit**
- I have developed an user interface for Movie Recommendation by using streamlit library inside PYCHARM.

  
![image](https://github.com/RahulSurenderSingh/Movie-Recommended-System-Content-Based/assets/136818857/9e8a85c6-7050-41b8-b958-d4b6ea6d3522)


# DATASET
- Download movies dataset from here
- https://www.kaggle.com/datasets/tmdb/tmdb-movie-metadata?resource=download


 

