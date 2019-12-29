# Deep Learning for the Life Sciences

I think that in the near future the biggest techonological improvements in society will come from advances in artificial intelligence and biology. So I've been trying to learn more about the intersection of artificial intelligence and biology. I decided to read the book, Deep Learning for the Life Sciences because it covers both topics.

If you want to become very rich or help a lot of people in the future, I recommend learning data science and biology. More specifically deep learning and genetics. I recently bought a book about deep learning and genetics.


## Introduction Life Science is Data Science
- The book begins by talking about how modern life sciences is increasingly driven by data science and algorithms
- As I have mentioned earlier, it's not so much that the algorithms we have are more sophisticated, it's that we now have access to smarter computers
- Put mroe bluntly, the computers have gotten way smarter, we on the other hadm have gotten marginally smarter at best.

## Introduction to Deep Learning
- deep learning at it's most basic level is simply a function, f() that transforms an input x, into an output, y: y = f(x) [7]
- The simplest models are linear models of the form y = Mx + b; which is essentially just a straight line [8]
- These are very limited by the fact that they can't fit most datasets. For example, height distribution of the average person would likely not fit  a linear model

- A solution to this is basically a multilayer perceptron, which is essentially just putting one linear function inside another linear function
y = M_2(B(M_1x + b_1)) + b_2
- B is called an activation function and transforms the linear function into a non-linear function

- As you put one of these functions inside another one you create what is called a multilayer perceptron
- An interesting blog post which explains the first Perceptron/Neural net, Rosenblatt's Perceptron ([blog post](https://towardsdatascience.com/rosenblatts-perceptron-the-very-first-neural-network-37a3ec09038a) (tk find paper not behind Medium paywall), [paper](tk add paper link))

### Training Models (13)
- To train the algorithm we need a loss function, L(y,y') where Y is the actual output and y' is the target value that we expected to get
- The loss function basically takes the two values to give us a value for how wrong we are
- Usually we use the Euclidean distance 
- Also does anyone know a good way of writing mathematical notation on Github? Maybe I should use latex for this review?
- For probability distribution you should use  cross entropy (really didn't understand this part)

