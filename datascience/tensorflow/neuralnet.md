
Put in the latex code for the thing you have written on your paper.


## How do neural networks work?
If we start by looking a the simplest examples of a ANN: inputs with no hidden layer and no activation function (fully connected layer)

![neuralregression](neuralregression.png)

We get:

$$ \begin{equation}
\begin{bmatrix} x_{1} & x_{2} & x_{3} \end{bmatrix}
\begin{bmatrix} w_{1} \\\\ w_{2} \\\\ w_{3} \end{bmatrix}
=x_{1} w_{1} + x_{2} w_{2} + x_{3} w_{3} \end{equation} $$

So here we see that we get the same equation as a multivariable linear regression.

$$ \begin{equation}
\begin{bmatrix} x_{1} & x_{2} & x_{3} \end{bmatrix}
\begin{bmatrix} w_{1} & w_{4} \\\\ w_{2} & w_{5} \\\\ w_{3} & w_{6} \end{bmatrix}
\end{equation} $$




## Activation functions.













Idea "forced neural networks" for faster learning.

Make networks learn faster by setting



How deep should a network be?
Question how many features do you think exists in the data you are trying to predict?



Should we use $$ x, x^2 $$ and so when doing data analysis?


Make a much more shallow network.

Search gradient loss in each additional layer of the network.
https://stats.stackexchange.com/questions/115258/comprehensive-list-of-activation-functions-in-neural-networks-with-pros-cons

http://cs231n.github.io/neural-networks-1/
