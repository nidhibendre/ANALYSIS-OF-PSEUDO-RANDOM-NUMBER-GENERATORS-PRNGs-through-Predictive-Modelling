# ANALYSIS-OF-PSEUDO-RANDOM-NUMBER-GENERATORS-PRNGs-through-Predictive-Modelling

Pseudo-random number generators (PRNGs) are deterministic algorithms designed to generate sequences of numbers that exhibit statistical properties similar to truly random sequences. However, they are not truly random because their outputs are entirely determined by their initial state, known as the seed, and the sequence of operations applied to it. This inability to generate truly “random” numbers poses issues in many sectors, ranging from cryptography and simulations to statistical modeling. 

Our project acknowledges this issue as we try to crack a widely-used PRNG (XORShift 128) by accurately predicting the sequence of random numbers it generates. Our goal was to create a model to predict the output of a PRNG.

<b>Problem Statement:</b> Given the last 4 generated numbers from a PRNG, can a neural network predict the next randomly generated number?


**Won first place at Northeastern University's Data Club's annual Snowball Competition**

