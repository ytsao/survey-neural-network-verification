This is a review paper, they summarized different abstract methods in neural network verification (feedforward neural networks). 

They are focusing on *abstract neural network* (ANN) which is meaning to reduce the number of neurons in network.

Most of ANNs are using *interval domain* to merge neurons and remove edges between neurons.
And they do not have specific method to reason this abstracted neural network, they just invoke MIP or SMT solver to verify.

---

Inspiring by this paper, there is another perspective to interpret *backward-forward analysis* (BFA).
In BFA, if the postconditions can be entailed before the output layer, then that is also representing we reduce the network size but it depends on the testing example. We do not have an unique abstracted form to verify all testing data.