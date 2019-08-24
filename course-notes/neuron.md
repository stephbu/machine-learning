# 1. The Biological Paradigm

Artificial Neural Networks are modelled on the Nervous System - neurons, which are a massive hierarchical network that controls biological function and cognition through communication

### 1.1.1

Caution to not over-extend current modelling as more than a metaphor
"computers in terms of brains", not "brains in terms of computers".
Historical temptation to compare brain to latest state of the art technology. e.g. pneumatics

Biological Neurons slow - nanoseconds to fire, but there are billions of them operating in parallel.

Book context is "systems whose structure is only partially predetermined".  That is 
the structure or code is used to design the network, only fulfilled by 
configuration and training of the network.  

> **Learning Algorithm** (1.1.1) : <i>adjustment of the parameters through an automatic adaptive method.</i>

Several dozen proposed models, confusing puzzle of approaches.

Questions for each Chapter:
- What can be computed with these networks
- How do these networks determine their structure in a self-organized manner?

### 1.1.2

ANN are another form of approach to computation.  1930's - 1940's explored 5 models of computational evaluation
- mathematical - abandoned at time focus on recursion theory
- logic-operational model (Turing Machines) - first show of "programming" though evaluation of a state-machine
- cellular automation - an early iteration of parallel computing models, such that all data was processed simultaneously.
Undirected network of discrete/atomic computational units, governed by simple rules and states.
- biological model - hierarchical multi-layer structure
- computer model - von Neumann architecture - sequential state machine or CPU containg a control unit that coordinates ALU, Memory, registers and IO.  Basis for modern processes, and execution such as threading

> **Recursion Theory** : <i>Study of generalized computability and definability.</i>

### 1.1.3 Elements of Computing Model
>Computation = storage (memory) + transmission (IO) + processing (CU/ALU)

## 1.2 Networks of neurons

Neuron embodies many elements of Computation.

### 1.2.1 Structure of neurons
Receives signals from incoming channels (*dendrites*).
Processes signals inside of cell body.
Outputs response signals if any using axon

> **Hebbian Learning**: *a synapse between two neurons is strengthened when the neurons on either side (input and output) have highly correlated outputs (i.e. when in input neuron fires, it frequently leads to an output neuron firing).

## 1.3 Artificial Neural Network

### 1.3.1 Networks of primative functions

Input parameters are channels + weights of input for channel
Output is f(input1.weight1,...inputn.weightn)
<!--stackedit_data:
eyJoaXN0b3J5IjpbLTE0ODUwMjAwMzVdfQ==
-->