# Supersingular Isogeny-based Criptography
This project provides a SageMath implementation of three protocols: Supersingular Isogeny Diffie-Hellman (SIDH), Supersingular Isogeny Public key and Supersingular Isogeny Zero-Knowledge (SIZK). This project is part of my undergraduate thesis.

## Instructions

In `Classes_and_functions.ipynb` all clases necessary for the execution of the protocols are defined. Then each of the other files is one of the protocols. 

1. Supersingular Isogeny Diffie-Hellman: When executing `SIDH.ipynb` the entire Supersingular Isogeny Diffie-Hellman protocol is performed. The last two cells contain the shared secret key,each one obtained by one of the two parts (must be the same).

2. Supersingular Isogeny Public-key: The program `SIPK.ipynb` is a simulation of a messaging app. There are three main blocks of code corresponding to the three possible actions. The first one is used to create a user (with its associated password). The second is used to send a message (from one user to another). The latter is used to read all received messages. When executing each of the 'action' cells, we will be guided through messages to fullfill the action. To do a simulation, we must execute all cells until the  ''' create user '''  cell. Then run one of the 'action' cells depending on what we want to simulate. (An example would be creating two users, then sending a message from one to the other and finally reading the message with the receiver user and password).

3. Supersingular Isogeny Zero-knowledge proof: When executing `SIZK.ipynb` the entire Supersingular Isogeny Zero knowledge proof protocol is performed. If the verification is done succesfully, the second-last cell will print 'Correct authentication'. The last cell prints the time elapsed for the verification.
