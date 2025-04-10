## numpy

#### np.mean()



#### coding process：


1. convert (num, width,  height,  3) into (num, width *  height * 3)

2. standardize our dataset，For example:![image-20250407224130019](C:\Users\11243\AppData\Roaming\Typora\typora-user-images\image-20250407224130019.png)

3. Mathematical expression of the algorithm, in this step, we should do :

   - Initialize the parameters of the model

   - Learn the parameters for the model by minimizing the cost  

   - Use the learned parameters to make predictions (on the test set)

   - Analyse the results and conclude

4. Building the parts of our algorithm

   1. Define the model structure

   2. Initialize the model's parameters

   3. Loop:

      -   Calculate current loss (forward propagation)

      -   Calculate current gradient (backward propagation)

      -   Update parameters (gradient descent)

   4. Forward and Backward propagation

      - Loss fuction and loss fuction's gradient

   5. Optimization, update the parameter using gradient descent

   6. Merge all function into a model

      

      

   

.	