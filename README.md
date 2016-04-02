Diffie Hellman
==========

A simple Diffie Hellman key exchange implementation for Discrete Mathematic class (2014). Written in HTML, CSS, and Javascript. Uses jQuery and Foundation framework.

Description
-----------
The program consists of 3 different sub-program. The first one is the public key generator, the second one is shared key generator, and the last one is cryptanalisis program which is basically a bruteforcer program.

Usage
-----
To run the app, clone this repo, and then open the ``index.html`` file.

**Get Public Key**

To get the public key you can enter a prime number, base (a primitive root of base), and integer (secret key) into its respective fields, and the program will generate the public key instantly.

**Get Shared Key**

To get the shared key, you can enter a prime number, your integer (secret key), and the public key pair of your partner, and the program will generate the shared secret key instantly.

**Cryptanalysis**

To bruteforce the shared secret between A and B, you need to enter the prime, base, and each user public key that is being used, and press the Bruteforce button.
