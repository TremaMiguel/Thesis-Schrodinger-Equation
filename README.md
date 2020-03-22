The Schrödinger Equation
------------------------
------------------------

This work is divided as follows:

## 1. Semiformal Derivation 

Taking into account the ```Wave-particle duality``` formulated, from 1905 to 1924, by Albert Einstein and Louis de Broglie, 
we seek a derivation to the ```Time-dependent``` case. Also, we briefly mention about the probabilistic interpretation that 
Max Born gave in 1926 to the equation.  

## 2. The time dependent equation

> ![formula](https://render.githubusercontent.com/render/math?math=-\frac{\hslash^2}{2m}\frac{\partial^2\psi(x,t)}{\partial{x^2}}+\mathcal{V}(x,t)\psi(x,t)=i\hslash\frac{\partial{\psi(x,t)}}{\partial{t}})

By formulating an ```Initial Value Problem``` we give a general solution when the initial condition ![formula](https://render.githubusercontent.com/render/math?math=\psi_{0}(x)\in\L^2(\mathbb{R},\mathbb{C})). Then, we'll
see that this solution was a strong one, for this reason, we develop the concept of ```test functions``` to find
out the condition to which ![formula](https://render.githubusercontent.com/render/math?math=\psi(x,t)) satisfies
the free Schrödinger equation in the weak sense. Finally, when considering a ```wave packet``` as initial condition
we develop the concepts of ```group velocity``` and ```phase velocity``` to arrive to the ```Slowly Varying Envelope
Approximation``` condition.

## 3. The time independent equation

> ![formula](https://render.githubusercontent.com/render/math?math=-\frac{\hslash^2}{2m}\Psi''(x)+\mathcal{V}(x)\Psi(x)=\E\Psi(x))

The above equation can be simplified to an ```eigenvalue equation``` where ***E*** are the eigenvalues associated to the Hamiltonian Operator. So, we would like to study the particle movement, but we notice that it depends on whether the energy is positive or negative.
For the first case, we have the ```infinite well``` where we can model the behavior of a ```pair solution``` and an ```odd solution```. Then, when considering positive energies, the ```finite well``` ![formula](https://render.githubusercontent.com/render/math?math=\mathcal{V}(x)=0) allow us to study the ```Quantum Tunneling effect```.


## 4. Operator Theory (The Schrödinger operator)

To add sauce to the taco, we develop the theory of the Schrödinger Operator. Before this, I recommend to read the section 2.1 to understand some concepts like  ```quadratically integrable```, the ```Holder inequality``` or ```vectorial space```. 

Chapter 5 is highly technical, we develop the theory of ```unbounded operators``` and some of their properties that would be required for the Schrödinger operator ![formula](https://render.githubusercontent.com/render/math?math=\Delta) + ![formula](https://render.githubusercontent.com/render/math?math=\mathcal{V}). Also, some of the concepts that we've seen in the previous chapters take a formal justification, from the point of view of functional analysis, to generalize the results. For example, the conditions for an operator to have positive eigenvalues. 

One of the key ideas of this chapter is that we could guarantee that the Schrödinger operator is ```self-adjoint``` if we could decompose the potential function ![formula](https://render.githubusercontent.com/render/math?math=\mathcal{V}(x)) as the sum of functions that belong to an ![formula](https://render.githubusercontent.com/render/math?math=\L^p)space. To achieve this, we provide a proof of the ```Kato-Rellich Theorem```.

