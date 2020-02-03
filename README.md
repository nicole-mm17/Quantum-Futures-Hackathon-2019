![Image of Logo](logo.png) ![Image of Logo](qmusic.png)
# Quantum Futures Hackathon 2019
## Humanizing Quantum - PianQ

Generating quantum music using Qiskit. 
We have developed a platform designed to help the general public understand quantum phenomena, such as superposition, and quantum computation, all using the language of music instead of mathematics. We have used one-to-one mapping between the musical notes of an octave, to eight single qubits.

The interactive and easy-to-use quantum piano interface, built using the Pygame library, performs specific operations (e.g. a Hadamard gate) on a quantum computer (IBM Q) or quantum simulator, using the Qiskit library. When the user presses a key associated with one of the notes on the virtual piano visible on the screen, this generates the relevant quantum logic gate on the screen that chances the state of the qubit, reproducing a specific sound frequency.

A change in volume demonstrates superposition, as maximum volume = |1> and minimum volume (i.e. no sound) = |0>; therefore, any volume intensity in between the two will be a superposition (i.e linear combination) of the two states, i.e. |ψ> = a|0> + b|1>, which is not possible classically. This interactive platform is designed to teach the user about quantum circuitry, so that when the process is reversed, they can appreciate what they are listening to. Therefore, the finale is an audio demo in which a quantum algorithm is translated into music, so you can listen to what a quantum algorithm sounds like. 
