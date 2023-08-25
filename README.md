# On the arithmetic of generalized Fekete polynomials. 

This Github repository contains our code and data for our paper [1]. Specifically, there are five files corresponding to the four cases that we consider in our paper; namely 
$$\Delta \in [-4p, 4p, -3p, 3p ].$$ The reason we have five files instead of four is due to the fact that the case $\Delta = -3p$ has a new phenomenon. Specifically, if $p \equiv 5 \pmod{8}$ then 
discrimination of $f_{\Delta}$ is a perfect square. Therefore, in this case, we look for a 2-4 cycle in the Galois group of $f$, instead of a $2$-cycle as in other cases. 


In each file, we also provide some numerical data corresponding to small $\Delta$. When we first worked on our project, these experimental data played a fundamental role in guiding our 
investigation. 

The structure of each file is as follows 

(1) We compute the smallest triple $(q_1, q_2, q_3)$ that guarantees that the Galois group of $g_{\Delta}$ is maximal. 

(2) To compute the Galois group of $f_{\Delta}$, we find the smallest prime number $q$ that gives the appropriate cycle (depending on whether the discrimination of $f_{\Delta}$ is
a square or not). 

[1] Jan Minac, Tung T. Nguyen, Nguyen Duy Tan, On the arithmetic of generalized Fekete polynomials, https://arxiv.org/abs/2206.11778. 





