# DS-Interview-questions
Flashcard like DS interview questions

## Data Science related questions

<pre>How can outlier values be treated?</pre>

<details>
  <summary>Answer</summary>
  
  1. Can be dropped if it's garbage value  
  -- e.g. height = abc ft, then it's string value instead of int or float, hence can be dropped  
  -- if it's extreme value, it can be removed
  
  2. If you cannot drop outliers, you can try  
  -- a different model. Data detected as outliers by linear models can be fit by nonlinear models => be sure to use the correct model  
  -- normalizing the data => the extreme data points are pulled to a similar range  
  -- you can use algorithms that are less affected by outliers; example would be random forest
  
</details>

<pre>Describe the steps of z-score scaling</pre>

<details>
  <summary>Answer</summary>
  
  1. Calculate mean  
  2. Subtract the mean from each value  
  3. Calculate the standard deviation  
  4. Divide by the standard deviation  
  Mathematical formula : {(sample value) - (the mean)} / (standard deviation)  

</details>

<pre>Why is it important to scale the data in terms of making heatmaps</pre>

<details>
  <summary>Answer</summary>
  
  Because otherwise the data are sparsely located, hence it wold make so many shades of heatmap. And we can only discern so many shades of colors.  
  The wider the range, the more subtle the difference in the shades. By tightly grouping the data, we use fewer shades and it's easier to see.  
</details>

<pre>What happens if there's outlier when you're making heatmap</pre>

<details>
  <summary>Answer</summary>
  
  This case, the standard deviation will be much bigger, the values near zero will get compressed a lot and it will be hard to separate them with only few shades.  
</details>

<pre>What are the difference between Supervised Machine Learning and Unsupervised Machine Learning? </pre>

<details>
  <summary>Answer</summary>
  
  1. Supervised ML
  -- Uses known and labeled data as input  
  -- Has a feedback mechanism  
  -- Most commonly used supervised ML algorithms are decision trees, logistic regression, and support vector machine  
  
  2. Unsupervised ML
  -- Uses unlabeled data as input  
  -- Doesn't have feedback mechanism  
  -- Most commonly used unsupervised ML algorithms are k-means clustering, hierarchical clustering, and apriori algorithm  
</details>


<pre>Explain the steps is making decision tree</pre>

<details>
  <summary>Answer</summary>
  
  1. Take the entire data set as input  
  2. Calculate entropy of the target variable, as well as the predictor attributes  
  3. Calculate your information gain of all attributes  
  4. Choose the attribute with the highest information gain as the root node  
  5. Repeat the same procedure on every branch until the decision node of each branch is finalized  
  
  
</details>

<pre>Differnce between clustering and classification/regression models</pre>

<details>
  <summary>Answer</summary>
  In classification and regression models, we are given a data set(D) which contains data points(Xi) and class labels(Yi). Where, Yi???s belong to {0,1} or {0,1,2,???,n) for Classification models and Yi???s belong to real values for regression models.  
  When it comes to clustering, we???re provided with a data set that contains only data points(Xi). Here we???re not provided with the class labels(Yi).
  
</details>

##### Template
<pre>Your Question</pre>

<details>
  <summary>Answer</summary>
  
  1. FirstPoint 
  -- 
  -- 
  
  2. SecondPoint
  -- 
  
</details>




