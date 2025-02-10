# AISTATS2025-446
This file is a brief manual for the submitted paper 'Parameter Estimation in State Space Models Using Particle
Importance Sampling' in the AISTATS 2025 conference. 

The main executions are in the format of .ipynb and on our computing source they were run in Python 3.0 on Jupiter notebook 6.5.4(in the Anaconda cluster). 
The compute worker is CPU: Processor 12th Gen Intel(R) Core(TM) i7-12700 2.10 GHz, with installed RAM 32GB, under the 64-bit operating system, x64-based processor. 
Execution times are based on independent runs on our computing source and may vary in different situations.

The main parts of the code in this folder are developed by the authors. There are pieces of code developed by Nicolas Chopin(2020, An Introduction to Sequential Monte Carlo) 
and Christopher Nemeth(2016, Particle Approximations of the Score and Observed Information Matrix for Parameter Estimation in State–Space Models With Linear Computational 
Cost) for specific implementation in some algorithms. For the corresponding code, any merit is attributed to them and any fault in implementation is to blame the authors. 


The file 'main_AR1.ipynb' contains numerical implementation in section 5.1 of the paper and should be supplemented by the file 'class_AR1.py'.
The files 'vanilla vs semi-online(1).ipynb' and 'vanilla vs semi-online(2).ipynb' contains illustrations in the figures presented in section 5.1.
The file 'main_SV.ipynb' contains numerical implementation in section 5.2 of the paper and should be supplemented by the file 'class_SV.py'.
The file 'main_SV_likelihood surface.ipynb' contains illustrations in the figures presented in section 5.2 in the paper and should be supplemented by the file 'class_SV.py'.
The file 'main_PAR.ipynb' contains numerical implementation in section 5.3 in the paper and should be supplemented by the file 'class_PAR.py'.
The file 'Final Results.ipynb'summarises all results obtained in the files above and the RMSE ratios are presented in section 5 of the paper.
