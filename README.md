# DS-Interview-questions
Flashcard like DS interview questions

## Data Science related questions

<pre>How can outlier values be treated?</pre>

<details>
  <summary>Answer</summary>
  
  1. Can be dropped if it's garbage value  
  - e.g. height = abc ft, then it's string value instead of int or float, hence can be dropped  
  - if it's extreme value, it can be removed
  
  2. If you cannot drop outliers, you can try  
  -- a different model. Data detected as outliers by linear models can be fit by nonlinear models => be sure to use the correct model  
  - normalizing the data => the extreme data points are pulled to a similar range  
  -- you can use algorithms that are less affected by outliers; example would be random forest
  
</details>



