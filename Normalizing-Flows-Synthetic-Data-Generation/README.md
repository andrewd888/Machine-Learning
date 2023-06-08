### Synthetic Image Dataset Generation via Normalizing Flows
----
Normalizing Flows are a method for constructing complex distributions by transforming a probability density through a sequence of invertible mappings. By repeatedly applying the rule for change of variables, the initial density ‘flows’ through the sequence of invertible mappings. At the end of this sequence we obtain a valid probability distribution and hence this type of flow is referred to as a normalizing flow.
The synthetic data generation process is simple. The schema is as follows:
 To begin with, we define a simple base distribution, e.g. a 2D Gaussian
- Define our custom bijectors(we will use bijectors from TensorFlow Probability)
- Apply the flow to the base distribution to obtain a transformed distribution
- Draw samples from the transformed distribution
- Construct training and testing image datasets
