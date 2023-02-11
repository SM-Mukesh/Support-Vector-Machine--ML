# Support-Vector-Machine--ML
## Model-1
### Objective:
  To build Machine Learning Model with Support Vector Machine for Classification of Breast Cancer (as Malignant or Benign)
 
### About Data:
  Breast cancer wisconsin (diagnostic) dataset
 --------------------------------------------

**Data Set Characteristics:**

    :Number of Instances: 569

    :Number of Attributes: 30 numeric, predictive attributes and the class

    :Attribute Information:
        - radius (mean of distances from center to points on the perimeter)
        - texture (standard deviation of gray-scale values)
        - perimeter
        - area
        - smoothness (local variation in radius lengths)
        - compactness (perimeter^2 / area - 1.0)
        - concavity (severity of concave portions of the contour)
        - concave points (number of concave portions of the contour)
        - symmetry
        - fractal dimension ("coastline approximation" - 1)

        The mean, standard error, and "worst" or largest (mean of the three
        worst/largest values) of these features were computed for each image,
        resulting in 30 features.  For instance, field 0 is Mean Radius, field
        10 is Radius SE, field 20 is Worst Radius.

        - class:
                - WDBC-Malignant
                - WDBC-Benign

### Result:
  This Dataset has performed well in Support Vector Classifier Algorithm with Accuracy of 0.92(92%),but to increase the performance of the model Hyperparameter tunning was done using Grid Search which increased the Accuracy from 0.92(92%) to 0.94(94%)
***********************************************************************************************************************************************************************  
## Model-2
### Objective:
  To build Machine Learning Model with Support Vector Machine for Classification of Iris Dataset
  
### About Data:
  The Iris flower data set or Fisher's Iris data set is a multivariate data set introduced by Sir Ronald Fisher in the 1936 as an example of discriminant analysis.
The data set consists of 50 samples from each of three species of Iris (Iris setosa, Iris virginica and Iris versicolor), so 150 total samples. Four features were measured from each sample: the length and the width of the sepals and petals, in centimeters.

The iris dataset contains measurements for 150 iris flowers from three different species.

The three classes in the Iris dataset:

Iris-setosa (n=50)
Iris-versicolor (n=50)
Iris-virginica (n=50)
The four features of the Iris dataset:

sepal length in cm
sepal width in cm
petal length in cm
petal width in cm

### Result:
  This Dataset has performed well in Support Vector Classifier Algorithm with Accuracy of 0.91(91%),but to increase the performance of the model Hyperparameter tunning was done using Grid Search which increased the Accuracy from 0.91(91%) to 0.96(96%)
