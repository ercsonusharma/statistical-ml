

SVM’s are initially meant to perform binary classification because of the way 
it creates the hyperplane to discriminate two classes. 
Hyperplane:
The hyperplane is defined by the equation ⟨vector(w) , vector(x) ⟩=0. 
This hyperplane partitions the training set into two sets. so as to classify into two classes.


For extending it to multi-class classification, one approach is to create several one-vs-all classifiers 
 Yet, another way is to formulate SVM as a K-class classification problem, based on the classical paper by Weston and Watkins[1]
 - https://www.elen.ucl.ac.be/Proceedings/esann/esannpdf/es1999-461.pdf .
 They compare it with K-binary or one-vs-all method show that it results in less support vectors.
