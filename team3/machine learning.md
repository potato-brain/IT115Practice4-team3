# Machine Learning

## Machine Learning
Machine learning is essentially feeding systems data that they can then use to learn from, and make predictions and decisions based on that data.

## Common Applications
These can be used for anything from predicting if someone is having a heart attack using EKGs, all the way to something less serious like teaching a computer to play a game like chess.

## Algorithms
An algorithm that can distinguish types of data is called a classifier. Classifiers typically reduce data into something called **features**. Features are used to classify types of data based on their characteristics.

## Data
To give a machine data to learn from, it needs **training data** or **labeled data**. A human must input and classify this data for the machine to use as a sample. Machines can learn in two main ways: **supervised** and **unsupervised learning**. Supervised learning can be thought of as learning with data already labeled, and unsupervised learning is where the data is unlabeled. There is also **semi-supervised learning**, where some data is labeled and some is unlabeled.

## Problems with Machine Learning
The job of machine learning algorithms is to minimize mistakes in decisions based on the training data. Typically, you cannot have 100% accuracy, and there will always be decision boundaries with overlaps. This area where some decisions cross the machine's boundary is called the **confusion matrix**.
The better the algorithm is designed, along with a large sample of high-quality data, the better the machine’s decision-making will be. One way to improve an algorithm is through better **decision trees** or **random forests**, which use logic structures like "if-then" statements or comparative operations like "over and under with values." Other techniques include **support vector machines**.

### Neural Networks
This can be improved even further by using **neural networks**. **Artificial Neural Networks (ANNs)** are systems inspired by biological brains to transfer information. The information input is usually real numbers, with outputs typically created through non-linear functions. Connections between these neurons are called **edges**. Similar to how brain neurons have action potentials, these artificial neurons have thresholds that adjust with **weights**, influencing how strongly they affect the output. The threshold can increase or decrease depending on learning. These neurons can also be layered, allowing for complex learning sequences that are not just linear (e.g., moving from layer 1 to layer 18).

### Conclusion
Machine learning started with very basic systems, like **Stockfish**, the chess engine that finds optimal moves, or email sorters. Over time, as computational power has increased, machine learning has evolved to detect faces, identify heart attacks using EKGs, and, eventually, diagnose cancer.

## Sources

- [Artificial Intelligence: A Modern Approach, 4th US ed. by Stuart Russell and Peter Norvig](https://aima.cs.berkeley.edu/)
- [Convolutional Deep Belief Networks for Scalable Unsupervised Learning of Hierarchical Representations](https://web.eecs.umich.edu/~honglak/icml09-ConvolutionalDeepBeliefNetworks.pdf) - Honglak Lee, Roger Grosse, Rajesh Ranganath, Andrew Y. Ng (Stanford University)