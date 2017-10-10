# Optimization-over-efficient-set-for-BOMILP-instances
Set of solved instances using OOES_Algorithm.cpp

## Instances.
We modify 25 BOMILPs used in [Boland et al. (2015b)](http://pubsonline.informs.org/doi/abs/10.1287/ijoc.2015.0646) to generate the instances. It is worth mentioning that these 25 BOMILPs are divided into 5 classes (each contains 5 BOMILPs). Each class is denoted by C*m* where *m* is the number of constraints of each BOMILP in that class. The number of variables and the number of constraints of each instance are equal, i.e., (n 1 + n 2 = m), and half of the variables are binary while the remaining variables are continuous.

From each BOMILP, we generate 10 different instances. The only difference between these 10 instances is the linear function. The coefficients of the linear function are randomly drawn from the discrete uniform distribution in the interval *\[-100,100]* for both continuous and integer variables. Note that for each BOMILP, the generated linear functions can be different. In total, *250* instances are provided. 

## Input File
Next is shown the format of the bi-objective mixed integer linear instances provided in this repository.
Problem example:

![Images](/Images/Example.jpg)
![Images](/Images/Obj_fun_example.jpg)

Description of the input file:

![Images](/Images/Input%20File.jpg)

All numbers must be separated by a single space or a tab space.
