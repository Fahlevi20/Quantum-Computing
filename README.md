# Quantum Computing

## Why Quantum Computing ?

In 1981, the Nobel laureate Richard Feynman asked, “What kind of computer are we going to use to simulate physics?”

*Nature isn’t classical, dammit, and if you want to make a simulation of Nature, you’d better make it quantum mechanical, and by golly it’s a wonderful problem, because it doesn’t look so easy.*

Richard Feynman speech can be used to see how powerful quantum computing could be to let us understand more about our universe, since quantum physics try to explain and understand how our universe is built from the deepest subatomic dimensions to huge macroscopic phenomena. What can lead as to ask ourselves if our classical compurters are going to be able to solve and deal with problems that nature by essence shows to be a quantum complex behavior, that most likely are exponential problems for our classical computers, like the nitrogen-fixing process on agriculture, where dealing with several atoms interections, as the number of atoms grows the dimesion of our problem grows exponencially, what is impossible for a classical computer to solve nowdays.

So the question is, how quantum computers could solve these kind of problems some day ? With a different model of treating information closer with how our universe and nature behave, from the deepest levels and beyond.

## Classical Bit vs Qubit

Our classical computers, those that we've in home, desktops, notebooks, cellphones all of them in the deepest level stores the information as different sequences of **0s** and **1s**, so as **0100100100** where each entrie is either 0 or either 1. What makes a huge difference when we compare it with how the quantum computers stores information and work with it, where a state 0 or 1 can be seen as a unitary vector state in a Hilbert space or a Qubit, in the computational basis, defined as:

![equation1](https://user-images.githubusercontent.com/48037841/69909312-34ec8180-13d8-11ea-9600-bfd827f04ea9.png#center)

![equation2](https://user-images.githubusercontent.com/48037841/69909352-19ce4180-13d9-11ea-8317-6df03033af8b.png)

![image1](https://user-images.githubusercontent.com/48037841/69909360-31a5c580-13d9-11ea-9e00-de38f4673812.png)

Where the scalars alpha and beta are used to see the amplitude of each state, or more generally, its probability to colapse over the possible states, which is like we could have all possible states at the same time, but we can only measure and see a small piece of this huge information.

## Quantum Superpostion and Entanglement

As we're dealing with quantum behavior some pretty important features of quantum mechanics that are used in quantum computing are the **Quantum Superposition** and the **Quantum Entanglement**. If were given to us a state $\psi$, when neither of its constants, are null, we say that this state is in **superpostion**. More generally, which means that before a potential measure a phisical system is partially over all possible existants theoretical states.

However when we measure it, it colapses to a unique state, so its like nature is doing a massive work, but it is willing to share with us just a small piece of it, a hint, for us to solve some very difficult problems.

If a state can not be writen by the tensor product of other states we've that this states is **entangled**, so as the wellknown Bell-State.

Where if we measure one of the Qubits we know exactly the state of the other, even if the other Qubit is in the other side of the galaxy, with is forbidden by the theory of relativity, since it would be faster then the speed of light, which is known as the *EPR Paradox*.

## Programming with Quantum Gates

While in Classical Computers works by applying simple boolean operators like *NOT, NAND, XOR, AND, OR*, Quantum Computers works with Quantum Gates, which mathematically speaking are unitary operators, that manipulates our state over the bloch sphere.
