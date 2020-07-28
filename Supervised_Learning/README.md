Introduction to Supervised Learning
For taking this session, you just need to remember the basics of linear algebra, which you have learned during your high school and a little bit python programming! That’s it!
Agenda: 
Quick review on algebra
Remember we had such functions:
Y=x , y=|x|,y=3x+1,… these basics equations are all we need! Y as a target has some relationships with its variables ( Xs)

Solving a real problem using linear algebra
Imagine function FX= (Square feet) *90000+(90000*(parking)) +(60000*(locker)+(30000*(bedrooms)). So familiar, isn’t it? aX+bY+cZ =F(x), a linear algebra function!
If you have such a function, you can easily calculate your property prices or find your ideal condo.
But what if we do not have it? No problem, we have two options:
Explore the function using tray and error (logic and algebra theorem)
Takes advantage of machine learning techniques to find such a function. (the machine will use the same methods to solve the problem but much faster than us!) we will see it in a bit.
For both scenarios, we need some sort of information, from well-known condos sales history lets call it dataset. This data set will have a column that shows the condos' prices. We can call it "Target" when we want to predict the price for our ideal condo.
The condos dataset also has square feet, parking, locker, bedrooms. These are the columns that we are going to work with. 

 


Introduction to Supervised learning: 
This is a new word, which you are going to hear it a lot during this lesson. But don’t worry if you don’t know what it is, you already used it! You just didn’t know the term of using it. Yes, the Condos dataset is a labelled dataset or a supervised dataset, and the method that we are using to predict the home price (using this dataset) named supervised learning.
The method that we are using to learn from the targeted dataset to predict the possible target value for a new record named supervised learning. It can be down on the paper using a mathematic equation, mostly algebra’s theory or by creating a specific machine learning model to predict the target value.
If you are interested in learning supervised learning in deep, you can take a look at the following link:
https://en.wikipedia.org/wiki/Supervised_learning
“Supervised learning is the machine learning task of learning a function that maps an input to an output based on example input-output pairs. It infers a function from labelled training data consisting of a set of training examples.” 

Introduction to Machine Learning
Machine learning: is a piece of code that can speed up the learning process and make an accurate prediction using mathematical equations. Like what we have done to predict the prices of the condos using Linear algebra.
Machine learning is a vast ocean in three main categories: supervised learning (like we are doing in algebra’s functions), Unsupervised learning and Natural Language Processing. Each of which has a number of subcategories that we are going to learn all during these courses.
Supervised learning Using Machine learning Techniques 
Back to the home pricing, the techniques that we used to learn from the sample dataset and find an appropriate function to predict the condos price named supervised learning.
The condos price is a continuous number. We can apply the same method to predict categorical items like a binary class (0,1), a character like (class A, Class B, Class C,…) or type of house ( Condos, Detach house, Semi-detached house) and call it classification approach.
Let take another look at the same dataset and try if we can predict the number of bedrooms. Don’t go far; lets can try machine learning techniques! For example, Logistic regression is a powerful regression classifier similar to the linear regression.
From the definition: “An explanation of logistic regression can begin with an explanation of the standard logistic function. The logistic function is a sigmoid function, which takes any real and outputs would be an integer [0,1,2,…]” the integer value is the predicted class!
 

Bum! You just learned the Idea of using machine learning for classification and prediction! We just have one more step to learn. 😊

Introduction to data preparation: 
Machine learning algorithms aren’t as intelligent as you are; they need some help to understand the data. Data preparation is the step we transform the raw data into an appropriate and readable format for the machine learning algorithms.
There are several approaches we can use; you are going to learn during these courses.
Let's see if we can improve our prediction accuracy using data normalization. Data normalization is noting but rescaling the dataset in a certain range, like between 0 to 1. For example:
List a=[100,2,16,10,200], min value =2, max value= 200
Mix/max function X=(X-min/max-min)
Normalized_a= [0.495, 0.0, 0.07, 0.040, 1.0]
We need to prepare our data for machine learning and transform all the features in the same range for better results. We are going to learn more in the future.
Let see if we can run a classification model using python’s codes. We are going to learn more in a working session. 

