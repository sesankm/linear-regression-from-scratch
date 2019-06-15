# linear-regression-from-scratch
implementation of linear regression with gradient descent from scratch

### Simple Linear Regression



**Loss Function**
<br>Evaluates the accuracy of the prediction model at a single training sample. 
<br>Squared error:
>$ L = (y_{true} - (m \cdot x + b))^2 $

m: weight
<br>b: bias
<br>N: number of training samples
<br>i: current training sample

**Cost Function**
<br>Average loss over entire training data.
<br>Mean Squared Error:
>$ C = \frac{1}{N}\sum_i^n(L) $  

>$ = \frac{1}{N}\sum_i^n((y_i - (m \cdot x_i + b))^2)$

Minimizing the cost function yields the optium weights biases.


**Gradient Descent**
<br>Gradient is essentially a derivitive. It finds the route of quickest descent to a local minima on a function, in this case the function is the Cost. We have to differentiate in terms of both parameters m and b.

>$ \frac{dC}{dm} = \frac{1}{N}\sum_i^n (-2x_i(y_i - (m \cdot x_i + b))) $

>$ \frac{dC}{db} = \frac{1}{N}\sum_i^n (-2(y_i - (m \cdot x_i + b))) $


**Training**
<br>1) make prediction
<br>2) calculate cost
<br>3) update parameters

>$ y_{pred} = m \cdot x + b $
