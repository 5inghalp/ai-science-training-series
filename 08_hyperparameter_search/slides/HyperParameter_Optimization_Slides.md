# Degrees of Freedom in Neural Networks Design for Scientific Data

![](./assets/Pasted%20image%2020220210140619.png)

---
# Degrees of Freedom in Neural Networks Design
![](./assets/Pasted%20image%2020220210140515.png)

---
# BiLevel Optimization Problem
![](./assets/Pasted%20image%2020220210140439.png) 

---
# [DeepHyper](http://deephyper.readthedocs.io) Overview
![](./assets/Pasted%20image%2020220210140714.png)

---
# Bayesian Optimization
![](./assets/Pasted%20image%2020220210140807.png)

---
# [DeepHyper](http://deephyper.readthedocs.io) Overview
![](./assets/Pasted%20image%2020220210140822.png)

---
# Configuring Neural Architecture Search
![](./assets/Pasted%20image%2020220210141008.png)

## How do we define a space of neural networks?
- A neural network search space can be represented as a directed acyclic graph with nodes and edges.
- Nodes represent possible operations, for example:  
    1. Add an identity layer
    2. Add a layer with 40 neurons
    3. Add a layer with 60 neurons
    4. Add a dropout operation
    5. Add a skip connection to another node
-   Nodes can be constant – (i.e., predefined and immutable during the search)
-   Nodes can be variable – (i.e., the search can tweak these to get better performance)
-   Each variable node has an upper bound on the number of operations (which may be expressed as a categorical variable). Edges define the flow of the tensor in the graph

---
# DeepHyper NAS-API
![](./assets/Pasted%20image%2020220210141042.png)

---
# DeepHyper NAS-API
![](./assets/Pasted%20image%2020220210141106.png)

---
# Exploring Search Space

![](./assets/Pasted%20image%2020220210141136.png)

---

# Searching for a Surrogate LSTM: Sea Surface Temperature Forecasting

![](./assets/Pasted%20image%2020220210141204.png)

---

# Scaling: Single Node, Cluster, Leadership Class

![](./assets/Pasted%20image%2020220210141235.png)


---
# The DeepHyper Project

### "Automated development of machine learning algorithms to support scientific applications"

![](./assets/Pasted%20image%2020220210141314.png)

---

# DeepHyper Community

![](./assets/Pasted%20image%2020220210141422.png)

---

# References
-   P. Balaprakash, M. Salim, T. Uram, V. Vishwanath, S. M. Wild. DeepHyper: Asynchronous hyperparameter search for deep neural networks. In 2018 IEEE 25th international conference on high performance computing (HiPC), 2018.
-   P. Balaprakash, R. Egele, M. Salim, S. Wild, V. Vishwanath, F. Xia, T. Brettin, and R. Stevens. Scalable reinforcement-learning-based neural architecture search for cancer deep learning research. In Proceedings of the International Conference for High Performance Computing, Networking, Storage and Analysis, 2019.
-   R. Maulik, R. Egele, B. Lusch, and P. Balaprakash. Recurrent Neural Network Architecture Search for Geophysical Emulation. In SC ’20: IEEE/ACM International Conference on High Performance Computing, Networking, Storage and Analysis, 2020.
-   R. Egele, P. Balaprakash, I. Guyon, V. Vishwanath, F. Xia, R. Stevens, Z. Liu.  AgEBO-Tabular: Joint neural architecture and hyperparameter search with autotuned data-parallel training for tabular data. In SC21:  International Conference for High Performance Computing, Networking, Storage and Analysis, (in press), 2021.
-   R. Egele, R. Maulik, K. Raghavan, P. Balaprakash, B. Lusch. AutoDEUQ: Automated Deep Ensemble with Uncertainty Quantification, (in review), 2021.
