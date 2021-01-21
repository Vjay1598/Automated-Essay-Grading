# Automated-Essay-Grading

## Dataset
Used the dataset obtained by the William and Flora Hewlett Foundation, which was made publicly available by their 2012 Kaggle competition. https://www.kaggle.com/c/asap-aes/data

## Algorithms and techniques used
Linear Regression model with 5-fold cross validation\n
Quadratic Weighted Kappa score as evaluation metric
Forward Feature Selection
Word2Vec Model

## Limitations
Most of our features are based on the structure and complexity of essay writing which for the purpose of our project turned out to be very useful. However, judging a paper by the features we used alone would be unfair. Most human graders also look at the writing style of the essays. Features like maturity in writing, emotive effectiveness, imagery, and meaningfulness would help in achieving a more human-like grade prediction. 
