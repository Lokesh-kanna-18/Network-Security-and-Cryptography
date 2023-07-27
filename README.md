# Network-Security-and-Cryptography
For This Project we used AES algorithm and CBC encryption to encrypt text, Image and  Video

Abstract

Using internet and network are increasing rapidly. Everyday a lot of files have been 
exchanging among users. Some of the files is sensitive that need to be protected from
intruders. Encryption and decryption algorithms play vital roles to protect original data from
unauthorized access. Various kind of algorithms already exist to encrypt or decrypt data. So 
this project is about implementation of Image, Video and File Encryption and Decryption 
using AES cryptography in CBC mode in a web browser.

Introduction


Advanced Encryption Standard (AES) algorithm is one on the most common and widely 
symmetric block cipher algorithm used in worldwide. This algorithm has an own particular
structure to encrypt and decrypt sensitive data and is applied in hardware and software all
over the world. It is extremely difficult to hackers to get the real data when encrypting by 
AES algorithm. Till date is not any evidence to crake this algorithm. AES has the ability to 
deal with three different key sizes such as AES 128, 192 and 256 bit and each of these 
ciphers has 128-bit block size. In this project we will be using AES in CBC mode with 256 
bits.

CBC (Cipher Blocker Chaining) is an advanced form of block cipher encryption. With CBC 
mode encryption, each ciphertext block is dependent on all plaintext blocks processed up to 
that point. This adds an extra level of complexity to the encrypted data.
The main feature of this scheme of encryption is that identical blocks of the clear text belong
to one message, are ciphered into various blocks of cipher text.
Here are the main characteristics of this scheme:
If one bit of the transferred message will be corrupted, it will damage the one more following 
block. Other blocks would be safe.
In case of loss or an insert at least one bit into cipher text, there will be a shift of bits and 
borders of blocks that will lead to a wrong decryption of all subsequent blocks of cipher text
The malefactor can add blocks by the end of the ciphered message, supplementing with that a 
clear text
Two identical messages have identical cipher texts if the same initialization vector 
(initialization vector (IV)) was used
