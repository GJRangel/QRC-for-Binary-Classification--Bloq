# QRC-for-Binary-Classification--Bloq

## Abstract
This report presents a novel Quantum Reservoir Computing (QRC) method applied to the Statlog
(German Credit Data) dataset, achieving an accuracy of 0.67 and a recall of 0.676 on the test
set under noise-free conditions. The proposed approach integrates quantum correlations into the
reservoir by encoding the m-th strongest feature relationships using Rzz and Ryy gates. Simulations
of real quantum hardware indicate that the mean squared error of the expected values remains
stable across the first six strongest correlations, highlighting the method’s robustness and potential
scalability. These results demonstrate the feasibility of QRC for binary classification tasks, paving
the way for future explorations in quantum-enhanced machine learning.

## Conclusions
In this work, we proposed a novel Quantum Reservoir Computing (QRC) approach tailored to binary classification tasks, integrating feature correlations into the reservoir’s design. By leveraging Hamiltonian time evolutions based on feature relationships, the method aims to encode both numerical and categorical data effectively within a quantum framework. The feature map and reservoir construction were carefully designed to ensure efficient representation of input data while maintaining manageable circuit depth. Preliminary analysis suggests that balancing circuit complexity with noise sensitivity is critical to achieving optimal performance.

This work is, to the best of my knowledge, a genuine contribution to the field, as Quantum Reservoir Computing has not been applied to this dataset in the manner presented here. Given the novelty of the approach, this first draft demonstrates promising results in terms of recall performance. However, further refinement is required, particularly through the exploration of alternative two-qubit gates and other methods to better represent the correlations between qubits. Additionally, investigating the approach under realistic noise models and testing its scalability to larger datasets will be crucial for assessing its practical applicability.

Moreover, this method could be further improved by incorporating graph reduction techniques to optimize the reservoir’s structure and simplify the representation of feature correlations. As this research was conducted during my free time alongside a full-time job, I was limited in the extent of experimentation that could be completed. Nonetheless, the insights gained from this initial study provide valuable groundwork for future work in quantum-enhanced machine learning, and I am eager to expand upon these findings with further investigation.
