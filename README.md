# language-recognition
Language recognition tool which uses different methods and has a user-friendly GUI

## General
This is a text language recognition project. Currently supports 2 languages: English and Russian.
3 different methods of language recognition are supported:
* Alphabetic
* N-gram
* Neural-network

Profiles for n-gram method and model for NN method are created <a href='https://github.com/DragunovK/text-lang-recognition-model'>here</a>.

## Technologies
* NLTK
* scikit-learn
* Tensorflow
* NumPy
* Pandas
* PyQt5
* bs4

## How to use
* Clone this repository
  ```
  git clone https://github.com/DragunovK/text-lang-recognition-model.git
  ```
* Install dependencies
  ```
  pip install requirements.txt
  ```
* Run
  ```
  python .\language_recognition.py
  ```
