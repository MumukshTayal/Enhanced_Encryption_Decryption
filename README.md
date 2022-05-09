# ENHANCED ENCRYPTION-DECRYPTION ALGORITHM BASED ON NUMERICAL METHODS

## Course Project for MA 202 [Numerical Methods]

***

## Overview

Information security has become a significant issue in today’s generation. With the increase in various threats and risks in the digital domains, there is an increasing need to come up with and develop newer ways of encrypting one’s crucial data and information. Therefore, an extra layer of protection shield is usually added on top of the basic encryption-decryption setup with the help of steganography. Steganography is a widely preferred and implemented technique due to the extra security that it provides. This is what we would like to focus on during this project.

## Mathematical Approach
In the practical world, one way functions are the functions which can be computed easily. It is like finding f(x) at a given value of x, but when we talk about images then it is difficult to obtain an image from a random input. One way functions are used to give an unique address to the input but there is no way to go back to get the original input. So naturally, one way functions are used in cryptography to encode the messages.
We can also check or verify whether they are accurate or not by knowing the input and output form the original phase. As part of this project, we have used three different types of numerical methods to approximate the root of the one way function in cryptography. From the conclusion perspective, we have compared the iterations and results of all the methods.

## A Brief idea about our approach

There are many algorithms in order to enhance the encryption method but our project aims to implement a symmetric encryption-decryption algorithm. As we have mentioned above, encryption is done by the one-way function and Diffie-Hellman is used to encrypt it.
For the encryption purpose, we have used numerical methods to determine the roots of the one-way, which is the cipher-text for our message. Decryption follows the exact opposite approach. We would also compare and present the results about the performance of the various numerical methods. 

## Results

![image](https://user-images.githubusercontent.com/72244706/167375616-b6afbc68-bfa0-438f-ba9b-ca3458d83bcd.png)


## Observation and Conclusion 

![image](https://user-images.githubusercontent.com/72244706/167375711-f3baf218-e97d-40b4-8fff-d4542aa237b7.png)
- The results of the comparison show that the Newton-Raphson method and Secant method are quite efficient, while methods like Bisection method do not work very efficiently for a larger length of text.
- From Figure above, it can be very well observed that the Newton-Raphson method and the Secant method take very less time and very less iterations for encrypting the same text message.
- The results we obtained hold with our general expectation that the Newton-Raphson method and the Secant method takes lesser time to converge.


### [Project Report](https://github.com/MumukshTayal/Enhanced_Encryption_Decryption/blob/main/Report.pdf)
### [Code](https://github.com/MumukshTayal/Enhanced_Encryption_Decryption/blob/main/Project_Code.ipynb)


***

<p align='center'>Created with :heart: by <a href="https://github.com/MumukshTayal">Mumuksh Tayal</a></p>
