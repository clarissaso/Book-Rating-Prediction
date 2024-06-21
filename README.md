# **Overview**

The goal of this Project is to build and critically analyse supervised Machine Learning methods to predict the ratings of books based on their titles, authors, descriptions and other features. There are three levels of rating, 3, 4 and 5, for each book.

This project aims to reinforce the largely theoretical lecture concepts surrounding data representation, clas- sifier construction, evaluation and error analysis, by applying them to an open-ended problem.

# **Data**
The information of book is collected from Goodreads, which is a platform that allows users to search its database of books, rate books and write reviews. The data files for this project are available via Canvas, and are described in a corresponding README.

In our dataset, each book contains:
* Book features: name, authors, publish year, publish month, publish day, publisher, language, page numbers, and description.
* Text features: produced by various text encoding methods for name, authors, and description. Each text feature is provided as a single file with rows corresponding to the file of book features.
* Class label: the rating of a book rating label (3 possible levels, 3, 4 or 5)
  
The training set contains the book features, text features, and the rating label, which is the “class label” of our task. The test set only contains the book and text features without labels.

The files provided are:
* *book rating train.csv*: the book features and class label of training instances.
* *book rating test.csv*: the book features of test instances.
* *book text features *.zip**: the preprocessed text features for training and test sets, 1 zipped file for each text encoding method. Details about using these text features are provided in README.
