# AWS Quantum Simulation with Amazon Braket SDK

Dive deep into the world of quantum computing with this project, which focuses on simulating a plethora of quantum algorithms. With quantum computing emerging as a pivotal frontier in computational technology, this repository stands as a cornerstone for those venturing into the domain. Utilizing the Amazon Braket SDK and Python, we endeavor to bridge theoretical quantum mechanics with practical applications.

## Overview of Algorithms

In quantum computing, the realms of superposition and entanglement form its bedrock. This repository shines a spotlight on a plethora of pivotal quantum algorithms:

### Bell's Inequality

Bell's Inequality forms the cornerstone of quantum mechanics, serving as a testament to the inherently non-classical nature of quantum systems. This experimentally verifiable phenomenon challenges classical intuitions about correlations and unveils the non-local character of quantum mechanics.

In this tutorial, we delve into a hands-on approach, showcasing how to simulate Bell's inequality experiment on Amazon Braket. By employing both a local simulator and a quantum processing unit (QPU), we demonstrate the violation of Bell's inequality, thereby reinforcing the quantum behavior of the system.

We begin by defining three distinct circuits, each acting on two qubits, which collectively serve as the experimental setup for the inequality test. Subsequent to the circuit definition, we harness the power of Braket's `LocalSimulator` to execute the experiment in a noise-free environment. The outcomes emphatically underline the violation of Bell's inequality, thereby mirroring the quantum character of the system.

For those keen on embarking on a real-world quantum experience, the tutorial also delineates the steps to run the Bell's inequality test on a QPU. Leveraging the `AwsDevice`, specifically the Oxford Quantum Circuits Lucy device, users can experience firsthand the intricacies of quantum computing. The cost metrics and task summaries included in the tutorial provide users with a transparent overview of the execution.

References:
- Bell, J. S. On the Einstein Podolsky Rosen Paradox. [Link](https://doi.org/10.1103/PhysicsPhysiqueFizika.1.195)
- Greenberger, Daniel M., et al. Bell’s Theorem without Inequalities. [Link](https://doi.org/10.1119/1.16243)

### Bernstein-Vazirani Algorithm
Imagine a scenario where you need to uncover a hidden number embedded within a function. The Bernstein-Vazirani algorithm can determine this hidden number in just one step, a feat unattainable by classical algorithms.

### CHSH Inequality
An extension of Bell's Inequality, the CHSH (Clauser, Horne, Shimony, Holt) Inequality provides a quantifiable metric to discern quantum from classical correlations. Violations of this inequality accentuate quantum mechanics' deviation from classical expectations.

### Deutsch-Jozsa Algorithm
Certain functions either have a consistent output or a balanced set of outputs. The Deutsch-Jozsa algorithm can efficiently discern between these two categories, showcasing quantum computing's prowess over classical methods.

### Grover's Search
In a vast unsorted database, finding a specific item is like finding a needle in a haystack. Grover's algorithm accelerates this process, reducing the search time from linear to square root in terms of the database's size.

### Quantum Approximate Optimization Algorithm (QAOA)
Addressing real-world optimization problems, QAOA demonstrates the potential of quantum computers. It offers a promising approach to tackle problems like the traveling salesman and other NP-hard challenges.

### Quantum Circuit Born Machine (QCBM)
Venturing into the world of quantum machine learning, the QCBM employs quantum circuits as generative models. This paradigm can potentially revolutionize data generation, classification, and more in the quantum machine learning spectrum.

### Quantum Fourier Transform
The Fourier transform is a cornerstone in signal processing. Its quantum counterpart, the Quantum Fourier Transform, streamlines computations, forming the backbone of several quantum algorithms, including Shor's algorithm.

### Quantum Phase Estimation (QPE)
At its core, QPE is about precision. It aims to determine the phase (or eigenvalues) of a unitary operator, a task fundamental to many quantum algorithms. Its applications span from quantum mechanics to cryptography.

### Quantum Walk
Unlike its classical counterpart, a quantum walk exhibits unique behaviors due to superposition and interference. It holds promise in algorithmic applications, including graph traversal and certain search problems.

### Shor's Algorithm
Modern cryptography's bulwark often rests on the difficulty of factoring large numbers. Shor's algorithm, if executed on a sufficiently powerful quantum computer, can shatter this foundation, necessitating new cryptographic approaches.

### Simon's Algorithm
Within a black-box function lies a hidden binary string. Simon's algorithm can uncover this concealed string with a notable efficiency advantage over classical algorithms.

## Tools and Techniques

**Amazon Braket**: Offered by Amazon, this tool arms users with a robust infrastructure, tailor-made for designing, testing, and executing quantum algorithms.

**Jupyter Notebooks**: An open-source tool that provides an interactive environment for writing and executing code. Each algorithm in this repository is presented as a Jupyter Notebook, ensuring an intuitive blend of code, visualizations, and narrative.

**Amazon SageMaker**: A fully managed service that provides developers and data scientists with the ability to build, train, and deploy machine learning models quickly. Its integration aids in scaling quantum simulations and incorporating ML techniques seamlessly.

**Dynamic Simulations**: Ensuring our content remains at the pinnacle of quantum research, our simulations echo the latest findings and methodologies in the quantum realm.

**Visualization Tools**: To foster a deeper comprehension, visual aids map out quantum outcomes and processes, translating abstract concepts into tangible visuals.
