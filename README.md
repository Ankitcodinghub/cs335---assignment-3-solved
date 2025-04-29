# cs335---assignment-3-solved
**TO GET THIS SOLUTION VISIT:** [CS335 – Assignment 3 Solved](https://www.ankitcodinghub.com/product/cs335-assignment-3-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;111162&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;1&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (1 vote)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CS335 - Assignment 3 Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 138px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            5/5 - (1 vote)    </div>
    </div>
Instructions

• This assignment should be completed individually.

• Do not look at solutions to this assignment or related ones on the Internet.

• The files related to the assignment are present in lab3-rollno.zip folder. Extract it and upload it on moodle in the same .zip format after completion and after replacing the string “rollno” with your actual roll number. For example, if you roll number is 00405036, then single zip folder that you will upload will be named “lab3-00405036.zip”. Also collate all the CS337 based theory solutions into ONE pdf file named answers.pdf. Include answers.pdf inside the zip folder mentioned above and submit the zip folder.

• Answers to all subjective questions need to be placed in single pdf answers.pdf including all plots and figures and uploaded.

• Only add/modify code between TODO and END TODO unless specified otherwise. You must not import any additional libraries.

1 Logistic Regression

1.1 CS 337: Logistic Regression

Consider the following formulation for extending the logistic regression to a multi-class classification setup:

Here, each wk is a class specific vector of dimension equal to the number of features in φ(x). This expression is called softmax. Note that this expression is slightly different from the multi-class logistic mentioned in Lecture 9 Each of the weight vectors wk are computed by optimizing the categorical cross-entropy loss function.

Here y(i) is a K length one-hot vector representing the label of the ith example, and W is a matrix having wk as its columns. Note that W is a matrix of dimensions (num features x num classes).

Show that cross entropy used to train a binary logistic regression (Eqn (3) of Lecture 9) is a special case of this. (1 mark)

1.2 Logistic Regression’s Decision surface

For this question, let us assume a 2 class dataset with features x ∈ Rd and labels y ∈ −1,+1. The decision rule obtained from a 2-class Logistic regression model with decision threshold θ ∈ (0,1) is given by

For simplicity let us assume that θ = 0.5. We know that the Sigmoid function, ( where s = wTx), as shown in the equation above is non-linear in w. Despite that, we call Logistic

Regression a linear model. Argue why that is the case. (1 mark)

1.3 CS 337: Multi Class Logistic Regression

Given the training data X,Y , we derive several binary features from it using a set of feature functions {φ}. For the scope of this question assume that each φj is a binary Indicator function indexed by words in the dictionary in a lexicographically sorted order. Thus φ(X) is a 1000 dimensional binary vector. φj(x) = 1 if the jth word is present in x (irrespective of the number of times the word appears) and 0 otherwise. These are popularly referred to as the Bag of Words features (without count values).

Qn (a) Specify what the feature vector φ would look like when

• x =”The food in the restaurant tastes good”

Qn (e) Let us now solve a numerical problem.

Qn (g) Next, we will maximize the log data likelihood w.r.t. the parameters of the model. Write the expression for log data likelihood as the difference of two terms, i.e., logP(D|W) =

Qn (i) This is a tricky part. Please be careful with the notation write your answer thoughtfully.

Qn (l) Analyze the expression in Qn (k). Carefully analyse the expression for a while, and explain in english what it conveys (1 mark)

1.4 CS 335: Lab Problems

(a) In this problem, we will try to predict the digit shown in the image. The dataset train X.npy contains features for images of size 28×28 as numpy array, train y.npy contains digits for corresponding images, for simplicity we will work with only for digits i.e. 1, 4, 7 and 9. We will implement logistic regression for this multi-class classification problem by making one vs all binary logistic regression classifiers for each of the 4 classes. Perform the following tasks.

Make sure you write an efficient vectorized implementation for each task. You are allowed to change the learning rate lr, maximum iterations epochs and sample size smaple size in function train multi class() in Assignment 3.ipynb.

(c) Consider a different evaluation metric F1 score, defined as the harmonic mean of precision and recall. Precision is defined as the fraction of positive outputs which are actually positive. Recall is defined as the fraction of actually positive samples predicted as positive. Formally, let’s denote TP as true positives, FP as false positives and FN as false negatives. Then recall, precision and F1 score are defined as follows:

recall =

precision =

2 ∗ recall ∗ precision

F1 =

recall + precision
