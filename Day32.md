# Day 32
**Intro to Machine Learning: Parameters in ML.**
* SVM C parameter: 
  * the regularization parameter which controls the trade-off between having a smooth decision boundary and classifying points correctly.
  * it is the regularization parameter and affects the smoothness of the decision boundary
  * **Low C:** maximises the margin(ensures the correctly classified points are actually very correct.
  * **High C:** focuses on getting more points classified correctly most often ending in complex decision boundaries.
* SVM gamma parameter: 
  * it defines how far the influence of a single training example reaches.
  * **Low values:** Points far from the possible decision boundary have a greater effect on the final decision boundary
  * **High values:** The decision boundary depends very much on the points nearby it.
* SVM strengths and weaknesses:
  * They do not perform well with very large datasets.
  * Performs poorly with overlapping classes.
  * Performance is good when the margin between classes is very clear.
* SVM mini project: 
  * Identifying the author of an email based on the words used in the mail.
  * Some of ML where quick running algorithms are preferrable
    * Credit card fraud detection and blocking
    * Voice recognition
  * How training size affects the prediction accuracy.
  * Playing around with the different of the parameters to see how they affect model performance
