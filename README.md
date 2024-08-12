# Secure Client-Server Communication using Diffie-Hellman Key Exchange and AES Encryption
Description:
 A Python implementation for secure client-server communications. A system designed to support a Diffie-Hellman key exchange for establishing a shared secret key between the client and the server. After that, this shared symmetric key will be used to encrypt messages with AES in CTR mode. The project gives an example of some of the key-related ideas of cryptography, such as generation and symmetric key exchange, key exchange, and message encryption.
 
 Features:
Diffie-Hellman Key Exchange: This is a self-contained algorithm for sharing a secret key over an insecure communication channel. It enables the client and server to generate the shared secret key without sending it from one to another. AES Encryption—CTR Mode: Tapes between a client and a server are encrypted. Multithreading: On the client side and server side, it makes it possible to send and receive messages simultaneously. Requirements:
Python 3.x
pycryptodome library, pip install pycryptodome

Files:
client.py: Client-side implementation
server.py: Server-side implementation

Usage:
Setting up the server:
 Run the server using python server.py.
Now the server will generate Diffie-Hellman parameters and wait for a client to connect.
Setup of the Client:
The client is run with python client.py.
After that, it connects to the server, finishes the key exchange, and starts communicating securely. 
Communication:
Now you can type messages from the client side to be sent to the server securely, and vice versa.
AES encryption key length is 128 bits because it is a good trade-off between security and performance.

License: 
This program is free and open-source under the MIT License.
