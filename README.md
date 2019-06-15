# linear-regression-from-scratch
implementation of linear regression with gradient descent from scratch

### Simple Linear Regression



**Loss Function**
<br>Evaluates the accuracy of the prediction model at a single training sample. <br><br>

![alt text](https://github.com/sesankmallikarjuna/linear-regression-from-scratch/blob/master/readme_files/LossFunc.png)


m: weight
<br>b: bias
<br>N: number of training samples
<br>i: current training sample

**Cost Function**
<br>Average loss over entire training data.<br><br>
![alt text](https://github.com/sesankmallikarjuna/linear-regression-from-scratch/blob/master/readme_files/Cost.png)


Minimizing the cost function yields the optium weights biases.


**Gradient Descent**
<br>Gradient is essentially a derivitive. It finds the direction of quickest descent to a local minima on a function, in this case the function is the Cost. We have to differentiate in terms of both parameters m and b.
<br><br>
![alt text](https://github.com/sesankmallikarjuna/linear-regression-from-scratch/blob/master/readme_files/grads.png)

