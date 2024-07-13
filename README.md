![image](https://github.com/abhayku2002/Iris-flower-classification-using-machine-learning/assets/34162485/8aa02cf7-5ad7-4c5a-bc1b-9d52b5cc9989)
# Iris Flower Classification Using Machine Learning <br/>
Machine learning is almost everywhere nowadays. It’s become more and more necessary day by day. From the recommendation of what to buy to recognizing a person, robotics, everywhere is machine learning. 
* In this project, we delved into the realm of supervised machine learning, specifically focusing on Iris Flower Classification. Leveraging six diverse machine learning models - k-Nearest Neighbors, Logistic Regression, Decision Tree, SVM, Naive Bayes, and Random Forest classifier - we aimed to construct robust models capable of accurately predicting iris flower species. Through extensive data visualization, analysis, and model construction, we gained valuable insights into the intricacies of the iris dataset and the performance of various algorithms. Our findings suggest that Logistic Regression emerges as the most accurate classifier among the six models tested. Moving forward, the overarching goal of supervised learning remains to build models that generalize well to unseen data, ensuring accurate predictions for future iris flowers beyond the scope of our training dataset. <br/>



## ABSTRACT <br>
The project scope entails employing diverse machine learning algorithms on the Iris dataset to classify iris flower species. <br/>
With 200 instances categorized into Setosa, Versicolor, and Virginica classes, the study includes model training, evaluation, and comparative analysis to discern the most effective algorithms, offering insights for botany and related fields. <br/> <br/>
The scope encompasses the following key elements: 
Dataset Analysis: Utilizing the Iris dataset containing 200 instances of iris flowers, each categorized into one of three classes: Setosa, Versicolor, and Virginica. The dataset includes features such as petal and sepal measurements
Model Training and Evaluation: Segmentation of the dataset into training and testing subsets, followed by the training of machine learning models on the training data. <br/>
The performance of each model is evaluated using metrics like accuracy, precision, and recall on the testing data.<br/> <br/>
Comparative Analysis: Conducting a comparative analysis of the performance of different machine learning algorithms in iris flower classification. 
This involves identifying the strengths and weaknesses of each algorithm in accurately categorizing iris flower species.<br/>

## Working Procedure <br/>

1.	Data Collection and Preprocessing: <br/>
* Collecting a comprehensive dataset of iris flower instances, including petal and sepal measurements for each sample. 
*	Preprocessing the dataset by handling missing values, removing outliers, and standardizing or normalizing the feature values to ensure consistency and facilitate algorithm convergence.
2.	Algorithm Selection: <br/>
*	Choosing suitable machine learning algorithms for iris flower classification, such as logistic regression, k-nearest neighbors, random forest, support vector machine, naive Bayes, and decision tree algorithms. 
*	Each algorithm is selected based on its appropriateness for the classification task and its potential to achieve high accuracy.
3.	Model Training: <br/>
*	Dividing the dataset into training and testing subsets to facilitate model training and evaluation. 
*	Training each selected algorithm using the training data, allowing the models to learn from the patterns present in the input features and their corresponding iris flower species labels.
4.	Evaluation Metrics: <br/>
*	Employing appropriate evaluation metrics, such as accuracy, precision, recall, and F1-score, to assess the performance of the trained models. 
*	These metrics provide insights into the algorithms' ability to correctly classify iris flower species and their overall effectiveness in solving the classification task

This program applies basic machine learning (classification) concepts on Fisher's Iris Data to predict the species of a new sample of Iris flower.

### Software and Libraries <br/>

Python 3.6.0 <br>
Anaconda 4.3.0 (32 bit) <br>
scikit-learn 0.18.1 <br>

The dataset for this project originates from the UCI Machine Learning Repository. The Iris flower data set or Fisher's Iris data set is a multivariate data set introduced by the British statistician and biologist Ronald Fisher in his 1936 paper The use of multiple measurements in taxonomic problems as an example of linear discriminant analysis.

The data set consists of 200 samples from each of three species of Iris (Iris setosa, Iris virginica and Iris versicolor).
Four features were measured from each sample (in centimetres): <be>

Length of the sepals <br>
Width of the sepals <br>
Length of the petals <br>
Width of the petals <br>

Three class for classification are as follows:</br>

* Iris-setosa <br>
* Iris-versicolor <br>
* Iris-virginica <br>

## Requirement

To install this package, [python3](https://www.python.org/), [pip](https://pypi.org/project/pip/), and [virtual environment](https://docs.python.org/3/library/venv.html) are required. <br>

For Windows users: </br>
[Install python3 and pip](https://phoenixnap.com/kb/how-to-install-python-3-windows)</br>
[Install virtual environment](https://programwithus.com/learn-to-code/Pip-and-virtualenv-on-Windows/) <br>


## Installation

Navigate to the cloned directory.

```bash
cd Iris-flower-classification-using-machine-learning
```

Create [virtual environment](https://docs.python.org/3/tutorial/venv.html) for Python.

```bash
python -m venv tutorial-env
```


Here, **tutorial-env** is the name of the virtual environment, you can name it as you like.

Activate virtual environment by the following command: </br>
To activate on windows:

```bash
Scripts\activate
```


Install pip packages from requirements.txt

```bash
pip install -r requirements.txt
```

## Run

On Windows run:

```bash
python classification.py
```


## Result <br/>
![image](https://github.com/abhayku2002/Iris-flower-classification-using-machine-learning/assets/34162485/766fd743-f54c-4bff-a07f-b5ed62569a39)

![image](https://github.com/abhayku2002/Iris-flower-classification-using-machine-learning/assets/34162485/45f24a90-408d-49f4-bb6f-b4171d875609)

