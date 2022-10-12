# Credit Scoring Prediction Using Random Forest Algorithm

Savina Irakleous, Postgraduate student in Data Science, University of Nicosia, Cyprus, mailto:savinairakleous@outlook.com

## ABSTRACT  
 It is known that regulators emphasize on risk management supervision and expect banks to be transparent for business or financial decision-making purposes after the financial crisis. Credit scoring models have a significant impact in financial risk management. They give a major influence on academic research and practical situations. In this research, we use Machine Learning especially random forest technique to estimate the probability of someone to experience financial distress in the next two years, and approach if he/she would be trustworthy to repay his/her loans, credit cards or future debts. The experiments in this research agrees with the literature and show that Random Forest model is suitable for easier and faster high accuracy. As well it reduces importantly the time spent on data management.

## Dataset

  This approach uses a Goldman dataset containing data about credit repayment difficulty rates among customers. The data set is made of 150,000 borrowers and it examinates the model with 12 features. Features are defined as: the number of times borrower has been past due over 30-59,60-89 days, but no worse in the last two years, the number of times borrower has been 90 days or more past due, the number of open credit lines and loans, the number of real estate loans or lines, the monthly income, the number of dependents, the total balance on credit cards and personal lines of credit except real estate and no installment debt like car loans divided by the sum of credit limits, the age, the Monthly debt payments, alimony, living costs divided by monthly gross income, the ID and the score.

## Methodology and Results  

  The purpose of this study is to build a model that borrowers can use to make the best financial decisions. With Machine Learning, especially random forest technique our model can locate the probability of someone to experience financial distress in the next two years, further if he/she would be trustworthy to repay their loans and credit cards or their future debts Random forest technique allows us to output a probability score and have a quick and easy change of our output to a simple binary classification problem.
In the specific approach random forest perform both classification and regression tasks, it undertakes dimensional reduction methods,treats missing values, outlier the values and other essential steps at the data exploration stage. Furthermore, it is an ensemble learning technique, where a number of models is combined to form a powerful model. The new model is based on attributes of classification assigns of each tree.

## The algorithm follows the following procedure:

Firstly, it builds the training set for growing the tree. Assume N is the number of cases in the training set. Then with replacement a sample of these N cases is taken at random. Secondly, if there are M input variables, a number of m<M is specified such that as each node, m variables are selected at random. The value of m is constant while we grow the forest. Each tree is grown to the largest extent possible and no pruning is done. In continue it predict new data by aggregating the predictions of the trees.
For data preprocessing we are normalizing our data in order to greater overall organization of our database. We also use outliers for detecting and dropping bad data. Output outliers affect the estimate of the leaf node they are in, but not the values of any other leaf node. We remove observations which are containing more than two outliers. Output outliers affect the estimate of the leaf node they are in, but not the values of any other leaf node. As well we did the appropriate data analytics in order to help lenders to understand better the data and get reliably results. Finally, we applicate random forest and then we found the accuracy o.

## Conclusions

In this disruptive era of Big Data, banks are considering the adoption of evolving technological capabilities. Overall credit scoring is a promising and impartial model that will give better insights from data, reduce cost and increase overall profitability. Random Forest model gives high accuracy easier and faster than Deep Learning method and reduce significantly the time spent on data management.

Furthermore, the Unsecure Lines_4, number of Open Credit Lines and Loans_1, the number of dependents_0.0 affect highly the credit score, while the number of Real Estate Loans or Lines_5, the number of times days past due does not significantly affect.

The accuracy rate of this model was 0.91952215 ≈ 91,95% on Goldman’s unseen test data. Given a relatively simple quantile- based approach which was used and in light of the fact that no parameter optimization was undertaken, I consider that this accuracy rate to be acceptable.

