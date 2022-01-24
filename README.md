# File-Encryption-and-Decryption-using-AES-and-DES
This is my Minor project in which i compared 2 of the strongest and famous algorithms on certain parameters

--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
INTRODUCTION
There is a considerable increase in the exchange of data over internet. This data may contains confidential information that needs to be secured from any third party access. Different kind of abuses is done with the data everyday like data leakage, corruption and many more which can be prevented by securing the data. Cryptography plays a vital role here. The prior focus of data security is to confirm the privacy while protecting personal data and other sensitive data.
 
Cryptography is a method of storing and transmitting data in a form that only those it is intended for can read and write. It is a science of protecting information by encoding it into unreadable format. Data cryptography is the scrambling of the content of data like text, images, audio and video to make it unreadable during transmission. It’s main goal is to keep the data secure from unauthorized access.

File Security is a major problem nowadays as data stored in the file can be very sensitive for any organization. It is much easier for a hacker to access any of the sensitive content stored in a file when file security not considered. Cryptography helps in achieving the data security which maybe stored in a file. It can be done by using many cryptographic algorithms.

Two of the most popular cryptographic algorithms in the field of file security are AES(Advanced Encryption Standard) and DES(Data Encryption Standard). Both algorithms differ and also leads in many different parameters compared to other cryptographic algorithms like less memory execution, lowest execution time and security levels.  


--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
PROBLEM STATEMENT
Tackling data security problems, there is a need to make a cryptographic
based file security system. There is a need of proper authentication and
security of data over the internet. The project aims to perform an empirical
study and implementation of the study to understand the performance
impact between 2 of symmetric cryptographic algorithms: AES and DES based
on file size, memory utilization, key sizes to get better understanding of
which algorithm is better than the other. 

This project also covers the security differences between both algorithms to
solve the essential problems faced at the time of data security.

--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
ALGORITHM USED
AES : 
AES(Advanced Encryption Standard)
AES algorithm is one of the most common and widely used symmetric block cipher algorithm. It used a particular structure to encrypt and decrypt data to provide the best security.  AES is hard to break by the attackers as it works on three different key sizes. It is a symmetric block cipher which means it uses same key to  encrypt and decrypt the data. 

 Can only accept a block size of 128 bits 

 Ability to deal with three different key sizes 
 128, 192, 256 bits, depends on which
 version to be used name as
 AES-128, AES-192 or AES-256 

 Works on symmetric key which means 
 faster than asymmetric, not easy to break

 Key sizes decide to the number of rounds  
 such as AES uses 10 rounds for 128-bit keys, 
 12 rounds for 192-bit keys and 14 rounds 
 for 256-bit keys

---------------------------------------------------------------------------------------------------------
 DES : 
 DES(Data Encryption Standard)
DES has been the most extensively used encryption algorithm standard. It is also a symmetric block cipher which means it also requires same key to encrypt and decrypt the data. DES has always been very vulnerable to attacks. DES method is used to store sensitive information or transmit information across insecure networks so that it cannot be read by anyone except the intended recipient.

 Input message of 64 bits can be encrypted using 
     the secret key length of 64 bits

 DES is faster algorithm when compared to RSA algo

 Likewise, AES it also uses symmetric key algorithm 
     which means it is very fast and secure

 DES is a block cipher algorithm where message 
     is divided into blocks of bits

 The new key is given as input for each round 

 All the operations such as initial permutation, 
     inverse permutation, substitution box, 
     expansion permutation, key schedule for key 
     generation are carried out with respect to standard tables


--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
CONCLUSION
Cryptography concept using AES and DES algorithm and implementing and comparing them on the basis of different aspects
Different parameters on the basis of which comparison will be done :
Memory Utilization
Key and block size 
Execution time
File sizes
AES and DES both algorithms work in their own way if we talk about rounds or different key sizes 
Detailed information and knowledge how data security is becoming vulnerable day-by-day, if strong and secure algorithms are not used 
Factual study and implementation of both algorithms considering different parameters by creating a console based program in C language


 



