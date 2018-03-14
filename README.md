Bayesian Classifier
=========================
The utility uses statistical methods to classify documents, based on the words that appear within them. A common application for this type of software is in email spam filters.

The utility must first be 'trained' using large numbers of pre-classified documents, during the training phase a database is populated with information about how often certain words appear in each type of document. Once training is complete, unclassified documents can be submitted to the classifier which will return a value between 0 and 1, indicating the probablity that the document belongs to one class of document rather than another.

How to use?
--------

1. Import `wordfrequency.sql`
2. Config `db_connect.php` file
3. Run `main.php`
