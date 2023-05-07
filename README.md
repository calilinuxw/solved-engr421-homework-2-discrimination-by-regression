Download Link: https://assignmentchef.com/product/solved-engr421-homework-2-discrimination-by-regression
<br>
<span class="kksr-muted">Rate this product</span>




In this homework, you will implement a discrimination by regression algorithm for multiclass classification in Matlab, Python, or R. Here are the steps you need to follow:

<ol>

 <li>Read Section 10.7.3 (4th edition) or Section 10.8 (3rd edition) from the textbook.</li>

 <li>You are given a multivariate classification data set, which contains 195 handwritten letters of size 20 pixels × 16 pixels (i.e., 320 pixels). These images are from five distinct classes, namely, A, B, C, D, and E, where we have 39 data points from each class. The figure below shows five sample figures from each class. You are given two data files:a. hw02_data_set_images.csv: letter images,b. hw02_data_set_labels.csv: corresponding class labels.</li>

</ol>

<ol start="3">

 <li>Divide the data set into two parts by assigning the first 25 images from each class to the training set and the remaining 14 images to the test set.</li>

 <li>Learn a discrimination by regression algorithm using the sigmoid function for this multiclass classification problem. You can use the following learning parameters.<pre>  eta &lt;- 0.01  epsilon &lt;- 1e-3</pre></li>

</ol>

5. Draw the objective function values throughout the iterations. Your figure should be similar to the following figure.

80 60 40 20

0

0 200

400 600 Iteration

800 1000

6. Calculate the confusion matrix for the data points in your training set using the discrimination rule you will develop using the estimated parameters. Your confusion matrix should be similar to the following matrix.

y_train

y_predicted 1 2 3 4 5 1 25 0 0 0 0 2 025 0 0 0 3 0 0 25 0 0 4 0 0 0 25 0 5 0 0 0 0 25

7. Calculate the confusion matrix for the data points in your test set using the parametric discrimination rule you will develop using the estimated parameters. Your confusion matrix should be similar to the following matrix.

y_test

y_predicted 1 2 3 4 5 1 13 1 0 0 0 2 1 11 0 0 2 3 0 0 14 0 0 4 0 1 014 0 5 0 1 0 0 12