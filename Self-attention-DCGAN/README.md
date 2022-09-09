# Self-attention-DCGAN

***An application on the SAGAN from https://github.com/franknb/Self-attention-DCGAN. I have created a single ipynb file for implementing the SAGAN and used inception score for validation.***

### Core files for running the code:

1. SAGAN_mnist.ipynb: A python notebook file for loading the data set, training and evaluation.



### Self-attention module:

1. Includes 3 layers : query, key and value with shape( Channels * N, N = Width * Height)

2. Matrix multiplication of query and key gives attention map which represents attention score of each pixel on other.

3. Attention weights are added back to the input layer.




### Referance:

[1] Han Zhang, Ian Goodfellow, Dimitris Metaxas, Augustus Odena: “Self-Attention Generative Adversarial Networks”, 2018;

Full paper: https://arxiv.org/pdf/1805.08318.pdf

[2] https://towardsdatascience.com/building-your-own-self-attention-gans-e8c9b9fe8e51
