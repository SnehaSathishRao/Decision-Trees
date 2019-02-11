# Decision-Trees
**Algorithm:**<br/>
Decision Trees are a type of Supervised Machine Learning (that is you explain what the input is and what the corresponding output is in the training data) where the data is continuously split according to a certain parameter. The tree can be explained by two entities, namely decision nodes and leaves. The leaves are the decisions or the final outcomes. And the decision nodes are where the data is split.<br/>

**Data:**<br/>
I have used Amazon data which contains summary of reviews that is featurized using NLP techniques(Bag of words,TfIdf,Average word2vec,TfIdf word2vec) gives higher dimensional.The Amazon data that is been used has already been pre-processed and loaded. <br />
**Summary**:  <br />


|     Model     |  Train auc-score   |   Test auc-score   |
| ------------- | ------------- |------------- | ------------- |
|    grid_BOW   | 0.8080595131739432 | 0.7673781072968167 |
|  grid_TF_IDF  | 0.810043223937983  | 0.7684279709100216 |
| grid_avgw2vec | 0.7494677213974306 | 0.7415708660917639 |
|  grid_ww2vec  | 0.7094475807638189 | 0.6913520851470105
