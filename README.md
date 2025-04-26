# csce633-homework-1--linear-models-solved
**TO GET THIS SOLUTION VISIT:** [CSCE633 Homework 1- Linear Models Solved](https://www.ankitcodinghub.com/product/homework-1-linear-models/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;127240&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;1&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (1 vote)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CSCE633 Homework 1- Linear Models Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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
Instructions for homework submission

a) There are two sections in this homework. Please write the solution to the first section in Latex. For the programming questions, please explain your thought process, results, and observations in a markdown cell after the code cells in a Jupyter Notebook. b) You need to submit a zip file:

• The name of the .zip file: FirstName LastName HW1.zip

• The zipped folder includes the following files:

– A pdf (generated using latex) for the math section: FirstName LastName HW1.pdf

– A .ipynb jupyter notebook file for the programming section: FirstName LastName HW1.ipynb

– A csv file with 2 main columns. One for the linear regression predictions with the name pred linear and one for the logistic regression predictions with the name pred logistic. file name: FirstName LastName preds.csv

c) Please start early 🙂

d) Total: 100 points

Math Questions

Problem 1: Gradient Calculation (8 points)

In this question you are required to calculate gradients for 2 scalar functions.

(1) Calculate the gradient of the function f(x,y) = x2+ln(y)+xy+y3. What is the gradient value for (x,y) = (10,−10)?

(2) Calculate the gradient of the function f(x,y,z) = tanh(x3y3) + sin(z2). What is the gradient value for (x,y,z) = (−1,0,π/2)?

Problem 2: Matrix Multiplication (8 points)

In this question you are required to perform matrix multiplication. (1)

=?

(2)

=?

Programming Questions

The goal of this section is to create two regression-based models to assess air quality. The data for this homework is uploaded on CANVAS (data train.csv) which includes the training data (features and labels) and (data test.csv) which includes the test data. Remember, the test data only contains the features we use for the training, but not the labels. For each row in the test data, you need to use the trained model to predict the corresponding labels. Each row of the data corresponds to a sample and the columns include the following information:

1. NMHC(GT): hourly averaged overall Non Metanic HydroCarbons concentration in microg/ m3

2. C6H6(GT): hourly averaged Benzene concentration in microg/m3

3. C6H6(GT): hourly averaged Benzene concentration in microg/m3

4. PT08.S2(NMHC): hourly averaged sensor response to NMHC

5. NOx(GT): hourly averaged NOx concentration in ppb

6. PT08.S3(NOx): hourly averaged sensor response for NOx

7. NO2(GT): hourly averaged NO2 concentration in microg/m3

8. PT08.S4(NO2): hourly averaged sensor response for NO2

9. PT08.S5(O3): hourly averaged sensor response for O3

10. T: Temperature in C

11. RH: Relative Humidity

12. AH: Absolute Humidity

13. PT08.S1(CO): TARGET VARIABLE – hourly averaged sensor response for CO

(a) Data Processing (4 points)

3. Does the data have any missing values? How many are missing? Return the number of missing values. (In pandas, check out isnul() and isnul().sum())

4. Drop all the rows with any missing data. (In pandas, check out dropna(). dropna() accepts an argument inplace, check out what it does and when it comes in handy.)

5. Extract the features and the label. The label is PT08.S1(CO).

(b) Exploratory Data Analysis (10 points)

1. Plot the histograms of all the features in the data. Do all the features have a normal distribution? Do you see any outlier values? Do you need to apply any normalization technique to these values? If so, you can transform your data in this step and explain your thought process in the corresponding markdown cell.

2. Pick 2 features and create a scatter plot to illustrate the correlation between these two features. Is there a high correlation between these features?

3. Compute the Pearson’s correlation between all pairs of variables 1-12. Assign the resulting correlation values in a 12×12 matrix C, whose (i; j) element represents the correlation value between variables i and j, i.e., C(i; j) = corr(i; j). Visualize the resulting matrix C with a heatmap and discuss potential associations between the considered variables. Note: You can use the ‘heatmap’ function from ‘seaborn’.

(c) (20 points) Linear Regression Implementation Implement a linear regression model from scratch to regress the target variable, Carbon monoxide (CO). (Remember: You can not use any libraries for the linear regression model.)

(d) (20 points) Logistic Regression Implementation Using the column PT08.S1(CO), create a binary label for this dataset where the values more than 1000 correspond to label 1 and the values less than or equal to 1000 correspond to label 0. Implement a logistic regression model from scratch to predict this binary label. (Remember: You can not use any libraries for the logistic regression model.)

(e) (10 points) Result Analysis – Linear Regression Perform a 5-fold cross validation. Compute RMSE for each validation set across 5 folds. Report average and standard deviation of RMSE values. Do you see a big change across different folds? How can you use the coefficient of this model to find the most informative features?

(f) (10 points) Result Analysis – Logistic Regression Perform a 5-fold cross validation. Compute accuracy, precision, recall, and F1 score for each validation set across 5 folds. Report the average and standard deviation of these metrics. Do you see a big change across different folds?

(g) (10 points) ROC Curve – Logistic Regression Use the logistic regression model from sklearn and repeat 5-fold cross validation. Then using roc curve package from sklearn.metrics, plot the ROC curve for each fold and compute the area under the curve. Is this result consistent with the results you obtained using the logistic regression model you implemented?

(h) Inference – Linear and Logistic Regression

1. Use the trained linear regression model and predict the PT08.S1(CO) value for the test data.

2. Use the trained logistic regression model and predict the PT08.S1(CO) binary value (the same label you created in step d) for the test data.

3. Save the predictions in a csv file with two main columns. One for the linear regression predictions with the name pred linear and one for the logistic regression predictions with the name pred logistic.

4. Add this csv file to your submission.
