# KRohancoder-Plagirism_Checke_with_AI_task-2

Plagiarism Detector in Python using Machine Learning Techniques, this is allowcated project by [Codeclause](https://codeclause.com/) 

Author: Rohan Kadam

Github: https://github.com/KRohancoder

# Discription 📀

The program reads text files from the folder, named as Docs under the current 
working directory. It reads all the text files having names Text_?.txt where ?
is to be replaced with any digit between 0 to 9.

The program applies word embedding techniques and first converts the textual 
data, read from the files, into an array of numbers (word vectors) using 
Term frequency-inverse document frequency (TF-IDF) method. For this purpose, 
TfidfVectorizer of scikit-learn built-in features is used.

All the pairs of word vecotrs are then processed for checking of any plagiarism 
between the corresponding text files. This is accomplished by computing the 
value of cosine similarity between the vectors representations of the concerned
text files.

Finally, a table of plagiarism percentage between every pair of files, read 
from the Docs folder is prepared along with presenting the result in Bar Graph.

# Project Difficulty level 🥇
Beginner

# Programming Language 🐍
Python

# Domain 🏥
Application

# Tools 🛠
This project requires that you have Python installed. Download it here.

It also requires the following Python packages, which can be installed via pip:

-sklearn
-numpy
-matplotlib

Then run it by double clicking on player.py!


# Features !

- plagirism
- text file 

# Editor's Interface Screenshot

![Screenshot](pp.PNG)

=======================================================================

## 📌 Opensource Programs

### [This project is a part of following Open Source Program](https://codeclause.com/)

![Screenshot](codeclause.jpg)


=======================================================================

# Contributing
Pull requests are welcome. If someone wants to contribute to this project can fork and add the Functionalities Or enhance the GUI.

## Happy Contribution ✨
