# Computing-the-Exact-LogConcave-MLE
This repository contains computations for the paper "Exact Solutions in Log-Concave Maximum Likelihood Estimation" by Alexandros Grosdos, Alexander Heaton, Kaie Kubjas, Olga Kuznetsova, Georgy Scholten, and Miruna-Stefana Sorea. 

## Mathematica code: alphaCertifiedSystemCreator.nb
This file contains the code that takes a rational-exponential objective function of the form (2.2) as an input and outputs a file with the system of critical equations that can be used by alphaCertified. This was used for Examples 4.12, 4.13, 4.14, and 4.15.

## alphaCertified code: system415, point415, settings415
These three files together can be used to readily verify the alpha-certification in Example 4.15. The user only needs to run the command

```
./alphaCertified system415 point415 settings415
```

from their terminal in a folder where alphaCertified and the three files are saved.

## Mathematica code: example416.nb
This file was used to evaluate the derivatives at the approximate solution  in Example 4.16.

