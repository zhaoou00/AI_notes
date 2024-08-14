# AI thoughts

## Binary Neural Network

### The current neural network based on real numbers
- The current neural network set up is based on available human concepts of real numbers.
- It has an input layer, some hidden layer, and an output layer.
- All the inputs and intermediate signals are "real number".
- The activation function is a non-linear function.
- With proper combination of the layers and activation functions, mathematically the neural network can reproduce any kind of outputs (functional completeness).
- The optimization of neural network is exclusively based on the properties of real numbers (transitional symmetry). 

### Using logic gates instead of real numbers
- The computer hardware is based on combinations of logic gates AND, OR, XOR, NOT etc. They are in no way aware of "real numbers". The concept of "real number" is not an absolute necessary intermediate step. It was forced on computer system to fit into human concepts.
- Forcing the concept of "real number" reduces the efficiency
- The non-lineariality is automatically built in the logic gates. Thereforewe do not need to choose an arbitrary activation function.

| AND   |   input1 |   input2 |   output |
|---:|---------:|---------:|---------:|
|  0 |        0 |        0 |        0 |
|  1 |        0 |        1 |        0 |
|  2 |        1 |        0 |        0 |
|  3 |        1 |        1 |        1 |

| OR   |   input1 |   input2 |   output |
|---:|---------:|---------:|---------:|
|  0 |        0 |        0 |        0 |
|  1 |        0 |        1 |        1 |
|  2 |        1 |        0 |        1 |
|  3 |        1 |        1 |        1 |

| XOR   |   input1 |   input2 |   output |
|---:|---------:|---------:|---------:|
|  0 |        0 |        0 |        0 |
|  1 |        0 |        1 |        1 |
|  2 |        1 |        0 |        1 |
|  3 |        1 |        1 |        0 |

| NOT   |   input1  |   output |
|---:|---------:|---------:|
|  0 |        0 |        1 |
|  1 |        1 |        0 |

To be functionally complete, only a subset of the logic gates are necessary. Therefore, neural network based on logic gates can reproduce any kind of outputs, too. 

- The construction and optimization of neural network should be directly on the logic gates. Having to base everything on real numbers reduces the efficiency of the system.
- The real number optimization approach can still be one of the important optimization strategy in the binary neural network.
- Other optimization algorithm need to be developed. For example: Straight-Through Estimator, specific loss functions etc.

- Furthermore, finding optimization strategy can be learned by AI. In other words, we can train an AI that can do optimizations on binary neural network. Thus we do no have to rely on arbitrary human-mind produced algorithms for optimization binary neural networks.


