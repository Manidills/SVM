# SVM

1. Hyperplane that comes with the boundaries { Margins and hyperplane } 
2. It works to convert the high dim space with kernal tricks

Kernal Types-

   1. polynomial kernal
   2. radial basis function kernal
   3. sigmoid kernal
   4. linear kernal

Combining these kernals gives more accuracy then using single kernal

Code-

  1. Load cancer dataset from sklearn
  2. StandardScaler()
  3. fit the model with linear kernal
  4. Note the metrics score
  5. fit the model with poly kernal
  6. Note the metrics value
  
  
Basically, support vector machine that use hyperplane with margines to seperate the points and use kernal tricks for better prediction.

But it takes much time to process then other machine learning algorithms because of kernal tricks
