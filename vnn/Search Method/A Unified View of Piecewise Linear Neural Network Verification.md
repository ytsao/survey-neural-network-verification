In this paper, they proposed a unified framework based on branch and bound algorithm.

They suggest that:
1. Global upper bound is setting as 0.
2. Using re-approximated method to evaluate lower bound by dual approach. (smart branching)
3. Proposed a novel branching strategy on input domain.

In addition, they compared two tools, Reluplex and Planet. To discuss the difference between them. They also provided different encodings on MaxPooling layer and Relu activation function.

---
In their experiments, they only did benchmarks on Collision Detection, ACAS, PCAMNIST dataset. We didn't know the performance on colorful dataset such as CIFAR10 dataset.

Still, in this framework, we don't know if it can be parallelized, it only focused on single thread mode. Moreover, it cannot be applied to other hyperbolic activation functions such as tanh and sigmoid because the branching strategy is based on the natural of piece-wise function.