# Apple-Fruit-Disease-Classification-using-Naive-Bayes-Algorithm
Classification of Apple Fruit Disease using Naïve Bayes Algorithm.
Here is the link to the dataset ->https://www.kaggle.com/datasets/kaivalyashah/apple-disease-detection

# Abstract
Apples are one of the most productive varieties of fruit in the world, with a high 
nutritional and medicinal value. However, numerous diseases affect apple production 
on a wide scale, resulting in significant economic losses. These diseases often go 
overlooked until just before, after, or after fruit has been processed. Many pathogens 
can be avoided with cultural traditions and (optional) fungicides, even if there are no 
cures for tainted fruit. However, accurate diagnosis is essential for determining the 
right management practices and preventing further losses. Apple scab, apple rot, and 
apple blotch are some of the most prevalent diseases that affect apples. 
The proposed approach will greatly aid in the automated identification and 
classification of apple diseases, according to our test results. We discovered that 
normal apples were easy to discern from diseased apples in our trial, and by 
implementing the naïve bayes algorithm with a classification accuracy of more than 
70.83333333333334 percent.

# Intro

1) Apple is a fruit that is eaten and cultivated all over the world, Because of its delicacy and 
high nutritional value.<br>
2) Numerous diseases affect apple production on a wide scale, resulting in significant economic 
losses.<br>
3) While working with the project we are trying to predict the apple diseases, while predicting 
diseases are represented as 0,1,2,3 in the model.<br>
 Blotch Apple - 0<br>
 Normal Apple - 1<br>
 Rot Apple - 2<br>
 Scab Apple – 3<br>
4) Apple Blotch:<br>
     Apple blotch is a fungus that causes black, uneven, or lobed edges on the fruit's surface<br>
 ![image](https://github.com/Tanujch03/Apple-Fruit-Disease-Classification-using-Naive-Bayes-Algorithm/assets/112710926/86d0d648-8b5d-4649-ac31-87200611ddae)

5) Apple Rot:<br>
     Apple rot causes somewhat sunken, oval brown or black patches that are often surrounded by a red halo.<br>
 ![image](https://github.com/Tanujch03/Apple-Fruit-Disease-Classification-using-Naive-Bayes-Algorithm/assets/112710926/99769eb6-e679-4029-abff-84b5b2a98755)

 

6) Apple Scab:<br>
      Apple scabs appear as gray or brown corky patches on the apple.<br>
 ![image](https://github.com/Tanujch03/Apple-Fruit-Disease-Classification-using-Naive-Bayes-Algorithm/assets/112710926/eb414a7a-6ff9-4696-8e02-cf366dcf6a8a)<br>

 



# PROBLEM STATEMENT:
1) As many farmers are suffering from the low productivity of apples due to the 
effects of major diseases such as apple rust and apple scab etc.<br><br>
2) Apple fruit diseases can result in major yield and quality losses. These diseases 
often go overlooked until just before, after, or after fruit has been processed.<br><br>
3) Naïve Bayes classifiers can be used for disease detection in plants and in the 
sense of helping farmers automatic detection of all kinds of diseases in plants to 
be detected because it has a very high accuracy.<br><br>
4) The main purpose is to detect the diseased fruits. Using python and using Naive 
Bayes Algorithm.<br><br>


# Organization of the work:<br>
1.Install the datasets(Apple fruit Disease dataset) from Kaggle.<br><br>
2.Load all the required libraries.<br><br>
3.The dataset contains two folder Train and Test.<br><br>
4.Load trained images from Train folder and Tested images from Test folder and 
preprocess it.<br><br>
5.splitting data into train and test.<br><br>
6.Fitting the Naïve Bayes Classifier.<br><br>
7.Checking the accuracy.<br><br>
8.Testing.<br><br>


# Software Architectural designs<br>

![image](https://github.com/Tanujch03/Apple-Fruit-Disease-Classification-using-Naive-Bayes-Algorithm/assets/112710926/d64b3857-01d6-480d-8c17-0104d09a3fac)

# Limitation/Constraints of the System<br>
This project does not give 100% accuracy, At first of testing stage, we got an accuracy of around 51%, we put all are efforts, and tried to improve the accuracy to 70.83333333333334%. Even though we can improve the accuracy further.

# Future Enhancement<br>

In further we can enhance the accuracy above 90%, by applying these methods.<br><br>

Image segmentation: At this stage to get an image with the same provisions with the intention of making it easier for the system to process the image is done cropping and then the image data used is converted into grayscale imagery with the aim to be able to display 1 color on each image after that is done noise removal to smooth the image so that in the process later can produce maximum results that are then done detection of canny edge lines that are useful as segmentation citra. on each preprocess done with the intention to give good results at the time of extracting texture characteristics.<br><br>

Feature extraction: By Grey Level Co-occurrence Matrix Method is a matrix whose components are the number of pairs of pixels with the same brightness degree, divided by d pixels and with an inclination angle of.
And by building a Mobile Application.<br><br>








