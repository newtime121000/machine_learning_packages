# machine_learning_packages
---
This repo contains two machine learning algorithms
1. polynomial regression
2. logistic regression


-<what i do in my project>
my finalterm project is classification model for classifying olivetti faces using python's sklearn.

-<the training dataset>
my dataset contains a set of face images taken between April 1992 and April 1994 at AT&T Laboratories Cambridge. The sklearn.datasets.fetch_olivetti_facesfunction is the data fetching, caching function that downloads the data archive from AT&T.There are ten different images of each of 40 distinct subjects. For some subjects, the images were taken at different times, varying the lighting, facial expressions such as open or closed eyes, smiling or not smiling, and facial details such as waring glasses or not. All the images were taken against a dark homogeneous background with the subjects in an upright, frontal position with tolerance for some side movement.
The image is quantized to 256 grey levels and stored as unsigned 8-bit integers; the loader will convert these to floating point values on the interval [0, 1], 
which are easier to work with for many algorithms. The “target” for this database is an integer from 0 to 39 indicating the identity of the person pictured; however, 
with only 10 examples per class, this relatively small dataset is more interesting from an unsupervised or semi-supervised perspective. 
The original dataset consisted of 92 x 112, while the version available here consists of 64x64 images. 
 
-<the algorithm that i choose>
I chose logistic regression algorithm because that algorithm is very suitable with my dataset.
Logistic regression, despite its name, is a linear model for classification rather than regression. 
Logistic regression is also known in the literature as logit regression, maximum-entropy classification (MaxEnt) or the log-linear classifier. 
In this model, the probabilities describing the possible outcomes of a single trial are modeled using a logistic function.

-<hyper-parameter of the function>
I set max_iter=300,C=200.
max_iter is to determine how many repetitions to perform, but the more repetitions, 
the higher the accuracy. However, if i do too much, it can cause overfitting problems, 
so i have to find the right point and I thought 300 was the right point.
C is cost function.
Cost function is a function that represents the difference between the predicted value and the actual result value. 
Accuracy may vary depending on how this is set, and 200 was designated as the most suitable value.
