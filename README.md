# Mercedes-Benz-Greener-Manufacturing
Can you cut the time a Mercedes-Benz spends on the test bench?

Overview
1. Since the first automobile, the Benz Patent Motor Car, was introduced in 1886, Mercedes-Benz has been consistent with significant automotive advancements. The passenger safety cell with crumple zone, the airbag, and intelligent assistance systems are examples of these advancements. Mercedes-Benz files almost 2000 patent applications per year, making it the European premium vehicle leader. Mercedes-Benz automobiles are market leaders in the premium automotive segment. Customers can get customized Mercedes-Benz of their dreams with a wide range of features and options.
2. Daimler engineers have devised a sophisticated testing method to verify the safety and reliability of each and every unique car configuration before it hits the road. However, without a powerful algorithmic method, optimizing the performance of their testing system for so many different feature combinations is hard and time-consuming. Daimler's production lines prioritize safety and efficiency as one of the world's largest premium automobile manufacturers.
3. Daimler seeks to combat the curse of dimensionality and cut the amount of time that automobiles spend on the test bench. Time delays occur as a result of a lack of coordination among manufacturing sub processes. Mercedes testing process must be extremely well-controlled, with only a few focalized perturbations.
4. Hence, objective of this case study is to accurately predict the testing time using Machine learning models. This will help in optimizing testing time; resulting into lower carbon emissions during testing.
5. This dataset provides an anonymized set of variables, each of which represents a unique Mercedes attribute. A variable could be 4WD, air suspension, or a head-up display etc.
6. File description- There are three files in dataset. Variables with letters are categorical. Variables with 0/1 are binary values.
a. train.csv – it contains the training set
b. test.csv - the test set, you must predict the 'y' variable for the IDs in this file
c. sample_submission.csv - a sample submission file in the correct format
7. There are no strict latency constraints. But model shall predict the time required for testing in few seconds to few minutes, not in hours.
8. Link to the data set: https://www.kaggle.com/c/mercedes-benz-greener-manufacturing/data
9. Since we need to predict the time required for testing of the vehicle which is a continuous variable, this problem comes under the category of regression problem in machine learning. Since this is a regression problem, we will use R2 as a model evaluation metrics.

