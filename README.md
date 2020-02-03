![Image of Logo](logo.png) ![Image of Logo](qmusic.png)
# Quantum Futures Hackathon 2019
## Humanizing Quantum - PianQ

Generating quantum music using Qiskit. 
We have developed a platform designed to help the general public understand quantum phenomena, such as superposition, and quantum computation, all using the language of music instead of mathematics. We have used one-to-one mapping where the musical notes of an octave are assigned to qubits.

The interactive and easy-to-use quantum piano interface, built using the Pygame library, performs specific operations (e.g. a Hadamard gate) on a quantum computer (IBM Q) or quantum simulator, using the Qiskit library. When the user presses a key associated with one of the notes on the virtual piano visible on the screen, this generates the relevant quantum logic gate on the screen that chances the state of the qubit, reproducing a specific sound frequency.

A change in volume demonstrates superposition, as maximum volume = |1> and minimum volume (i.e. no sound) = |0>; therefore, any volume intensity in between the two is a superposition (i.e. linear combination) of the two states, i.e. |ψ> = a|0> + b|1>, which is not possible classically. This interactive platform is designed to teach the user about quantum circuitry, so that when the process is reversed, they can appreciate what they are listening to. Therefore, the finale is an audio demo in which a quantum algorithm is translated into music, so you can listen to what a quantum algorithm sounds like. 


## Our Motivation and Future Vision

The motivation behind creating this project is to try and outsource quantum knowledge to the general public, as we want to move away from the silos of knowledge we have today, where less than 1% of the population have an understanding of quantum. Currently, laws cannot keep up with technology and this problem is likely to only get worse. Hence, our privacy, and potentially even our human rights, are at risk. Therefore, we believe improving education is the key to minimising this risk and giving people back control.

The reason we think our idea is so important is because in the future, we hope we can finish developing this educational tool and use it to create an array of resources to be used in primary schools to help give children a quantum intuition. Targeting children at this young age is ideal, as they don’t have classical logic and thinking as instilled in them.

Pushing complex science into the realms of general knowledge will not only empower people, but this bottom up approach will also help the acceleration of science, as we can harness the potential and creativity of the collective population.
