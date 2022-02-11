### classification representations
- Use a one hot vector to represent different classifications of labels
- Take the weighted sum of nodes which ends up with the three classes
- we want our output to be a probability distribution ocer classes, and pick argmax as the class label
- To get the probabilities, we need to normalize the output so that its sum adds up to 1
- Softmax is an activation function which maps the outputs with probabilities
- 