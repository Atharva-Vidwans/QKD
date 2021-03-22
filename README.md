# QKD

What is key distribution? Secure communication relies on the ability of the sender (Alice) to encrypt the message in a way that the receiver (Bob) can decrypt it but not an eavesdropper. This security is often accomplished with the use of a key, which is a piece of information known only to the sender and receiver and enables them to decrypt and encrypt the message. If a key can be securely distributed between the sender and receiver, the encrypted message can be securely sent over a public channel, since without the key, the probability of successfully decrypting the message is tiny.

Practically, a key is just a bitstring - a sequence of 1s and 0s, that is uniquely known only to Alice and Bob, the two communicating parties.

Therefore, the problem of secure communication boils down to secure key distribution. QKD is unique because security against eavesdropping is guaranteed by the laws of quantum mechanics, as opposed to the computational complexity of certain functions, which is what is used in classical key distribution.

Attached algorithm implements Quantum Key Distribution using BB84 protocol with and without Eavesdropper.
  
