# Quantum-circuits-code
Repository of quantum circuit code examples:

[**Shor Algorithm**](https://bitbucket.org/spilab/quantum-circuits-code/src/main/Shor_algorithm.py)

Shor's algorithm is a quantum computer algorithm for finding the prime factors of an integer.

![Shor](images/Shor_algorithm.jpg)


[Here](https://algassert.com/quirk#circuit={%22cols%22:[[%22H%22,%22H%22,%22H%22,%22H%22],[%22X%22],[%22X%22,%22X%22,%22X%22,%22X%22],[1,%22%E2%80%A2%22,%22X%22],[1,%22X%22,%22%E2%80%A2%22],[1,%22%E2%80%A2%22,%22X%22],[1,1,%22%E2%80%A2%22,%22X%22],[1,1,%22X%22,%22%E2%80%A2%22],[1,1,%22%E2%80%A2%22,%22X%22],[%22%E2%80%A2%22,1,1,%22X%22],[%22X%22,1,1,%22%E2%80%A2%22],[%22%E2%80%A2%22,1,1,%22X%22],[%22Measure%22,%22Measure%22,%22Measure%22,%22Measure%22]]}) is available the implementation in quirk 


[**Bernstein-Vazirani**](https://bitbucket.org/spilab/quantum-circuits-code/src/main/Bernstein-Vazirani.py)

Algorithm that tries to learn a string encoded in a function.

![Bernstein-Vazirani](images/Bernstein-Vazirani.jpg)

[Here](https://algassert.com/quirk#circuit={%22cols%22:[[%22H%22,%22H%22,%22H%22],[1,1,1,%22X%22],[1,1,1,%22H%22],[%22%E2%80%A2%22,1,1,%22X%22],[1,%22%E2%80%A2%22,1,%22X%22],[1,1,%22%E2%80%A2%22,%22X%22],[%22H%22,%22H%22,%22H%22],[%22Measure%22,%22Measure%22,%22Measure%22]]}) is available the implementation in quirk 


[**Grover Algorithm**](https://bitbucket.org/spilab/quantum-circuits-code/src/main/Grover_algorithm.py)

Algorithm for searching an unordered sequence of data with N components in time O.

![Grover](images/Grover_algorithm.jpg)


[Here](https://algassert.com/quirk#circuit={%22cols%22:[[%22H%22,%22H%22],[1,%22X%22],[1,%22H%22],[%22%E2%80%A2%22,%22X%22],[1,%22H%22],[1,%22X%22],[1,%22H%22],[1,%22Measure%22]]}) is available the implementation in quirk 


[**Deutsch–Jozsa Algorithm**](https://bitbucket.org/spilab/quantum-circuits-code/src/main/Deutsch–Jozsa_algorithm.py)

Algorithm that determines if a function is balanced or constant.

![Jozsa](images/Jozsa_algorithm.jpg)

[Here](https://algassert.com/quirk#circuit={%22cols%22:[[%22H%22,%22H%22,%22H%22],[%22X%22,1,%22X%22,%22X%22],[1,1,1,%22H%22],[%22%E2%80%A2%22,1,1,%22X%22],[1,%22%E2%80%A2%22,1,%22X%22],[1,1,%22%E2%80%A2%22,%22X%22],[%22X%22,1,%22X%22],[%22H%22,%22H%22,%22H%22],[%22Measure%22,%22Measure%22,%22Measure%22]]}) is available the implementation in quirk 


[**Simon Algorithm**](https://bitbucket.org/spilab/quantum-circuits-code/src/main/Simon_algorithm.py)

The goal of Simon's algorithm is to determine if f is one-to-one or two-to-one, which we will do by directly finding the secret string s.

![Simon](images/Simon_algorithm.jpg)

[Here](https://algassert.com/quirk#circuit={%22cols%22:[[%22H%22,%22H%22,%22H%22],[%22%E2%80%A2%22,1,1,%22X%22],[1,%22%E2%80%A2%22,1,1,%22X%22],[1,1,%22%E2%80%A2%22,1,1,%22X%22],[1,%22%E2%80%A2%22,1,1,%22X%22],[1,%22%E2%80%A2%22,1,1,1,%22X%22],[%22H%22,%22H%22,%22H%22],[%22Measure%22,%22Measure%22,%22Measure%22]]}) is available the implementation in quirk 


[**Travelling Salesman Problem (TSP)**](https://bitbucket.org/spilab/quantum-circuits-code/src/main/TSP.py)

The goal of TSP in quantum computing is to find the shortest possible route that visits a set of cities exactly once and returns to the starting city.

![TSP](images/TSP.jpg)

[Here](https://algassert.com/quirk#circuit={%22cols%22:[[%22H%22],[1,%22X%22,%22X%22],[%22X%22,%22%E2%80%A2%22],[%22X%22,1,%22%E2%80%A2%22],[%22H%22],[%22Measure%22,%22Measure%22,%22Measure%22]]}) is available the implementation in quirk 


[**Quantum Teleportation**](https://bitbucket.org/spilab/quantum-circuits-code/src/main/teleportation.py)

Quantum teleportation instantly transfers the condition or "state" of one quantum particle to another distant one without sending the particle itself.

![Teleportation](images/teleportation.jpg)

[Here](https://algassert.com/quirk#circuit={%22cols%22:[[1,%22H%22],[1,%22%E2%80%A2%22,1,1,%22X%22],[%22H%22],[%22%E2%80%A2%22,%22X%22],[%22H%22],[%22Measure%22,%22Measure%22],[1,%22%E2%80%A2%22,1,1,%22X%22],[%22%E2%80%A2%22,1,1,1,%22Z%22]]}) is available the implementation in quirk 


[**Quantum Phase Estimation**](https://bitbucket.org/spilab/quantum-circuits-code/src/main/phase_estimation.py)

Quantum phase estimation is one of the most important subroutines in quantum computation. It serves as a central building block for many quantum algorithms.

![phase_estimation](images/phase_estimation.jpg)

[Here](https://algassert.com/quirk#circuit={%22cols%22:[[%22H%22,%22H%22,%22H%22],[1,1,1,%22X%22],[%22%E2%80%A2%22,1,1,%22Z^%C2%BC%22],[1,%22%E2%80%A2%22,1,%22Z^%C2%BC%22],[1,%22%E2%80%A2%22,1,%22Z^%C2%BC%22],[1,1,%22%E2%80%A2%22,%22Z^%C2%BC%22],[1,1,%22%E2%80%A2%22,%22Z^%C2%BC%22],[1,1,%22%E2%80%A2%22,%22Z^%C2%BC%22],[1,1,%22%E2%80%A2%22,%22Z^%C2%BC%22],[%22Swap%22,1,%22Swap%22],[%22H%22],[%22%E2%80%A2%22,%22~16c9%22],[1,%22H%22],[%22%E2%80%A2%22,1,%22~gf1o%22],[1,%22%E2%80%A2%22,%22~16c9%22],[1,1,%22H%22],[%22Measure%22,%22Measure%22,%22Measure%22]],%22gates%22:[{%22id%22:%22~gf1o%22,%22name%22:%22U(-pi/4)%22,%22matrix%22:%22{{1,0},{0,%E2%88%9A%C2%BD-%E2%88%9A%C2%BDi}}%22},{%22id%22:%22~16c9%22,%22name%22:%22U(-pi/2)%22,%22matrix%22:%22{{1,0},{0,-i}}%22}]}) is available the implementation in quirk 

[**Quantum Fourier Transform (QFT)**](https://bitbucket.org/spilab/quantum-circuits-code/src/main/QFT.py)

The Quantum Fourier Transform (QFT) is the quantum implementation of the discrete Fourier transform over the amplitudes of a wavefunction

![phase_estimation](images/QFT.jpg)

[Here](https://algassert.com/quirk#circuit={%22cols%22:[[%22H%22,%22H%22,%22H%22],[1,%22X%22,%22X%22],[%22H%22],[%22Z%22,%22%E2%80%A2%22],[%22Z^%C2%BD%22,1,%22%E2%80%A2%22],[1,%22H%22],[1,%22Z%22,%22%E2%80%A2%22],[1,1,%22H%22]]}) is available the implementation in quirk 


[**Quantum approximate optimization algorithm (QAOA)**](https://bitbucket.org/spilab/quantum-circuits-code/src/main/QAOA.py)

Quantum algorithm that are used to solve optimization problems.

![QAOA](images/QAOA.jpg)

[Here](https://algassert.com/quirk#circuit={%22cols%22:[[%22Rxft%22,%22Rxft%22],[],[%22%E2%80%A2%22,%22X%22],[%22Rxft%22,%22Rxft%22],[],[1,%22Rxft%22],[],[%22%E2%80%A2%22,%22X%22],[%22Rxft%22],[],[1,%22Measure%22],[%22Measure%22]]}) is available the implementation in quirk 



*The examples have been selected from the official IBM and Qiskit documentation:*

https://qiskit.org/documentation/

https://quantum-computing.ibm.com/composer/docs/iqx/example-circuits