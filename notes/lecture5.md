### Backpropogation
- Chain rule: $\frac{dz}{dx} = \frac{dz}{dy} \frac{dy}{dx}$
- $f = (a + b)(b + c)$ with $a = -1, b = 3, c = 4$
- ![backprop](https://miro.medium.com/max/1400/1*azqHvbrNsZ8AIZ7H75tbIQ.jpeg)
- Feed forward is the opposite of back propogation
- Solved back prop
- ![solved](https://miro.medium.com/max/1400/1*GEpvvmhoj0yRTi_kpDS6Eg.png)
- Check out this article for more [Info](https://medium.com/spidernitt/breaking-down-neural-networks-an-intuitive-approach-to-backpropagation-3b2ff958794c)

### Vanishing Gradient
- the gradient starts to vanish when you start adding more layers?
- Look at this article for more [info](https://towardsdatascience.com/the-vanishing-gradient-problem-69bf08b15484)
- Gradient of sigmoid has an interesting property it's replaced by relu tho
- tanh activation function is kinda like the sigmoid function

### Weight Initialization
- Xavier initialization is a popular choice of initializing weights
- It sets a layer's weights to values chosen from a random uniform distribution

### Regularizing Neural Networks
- L2-regularization penalizes the norm of the weights by adding...
- Dropout regularization averages predictions of different models to regularize...
- is dropout regularization similar to nested regression models?
- ![dropout](https://miro.medium.com/max/1044/1*iWQzxhVlvadk6VAJjsgXgg.png)