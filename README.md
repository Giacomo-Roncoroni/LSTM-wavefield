# LSTM-wavefield
Codes for refering to the introductory parte of the PhD thesis entitled Long-Short-Therm Memory in Active Wavefield Geophysical Methods.
Specifically, it refers to Chapter 3, "explainable AI". 

## 00_data_generation
This folder refers to Chapter 3.1 of the thesis and contains the notebook to generate random velocity models and to creata a noise dataset with a convolutive approach described in Equation 3.2 of the thesis. 
In order to run the codes you will need an environment with: numpy, scipy, matplotlib, bruges (https://pypi.org/project/bruges/) and wiggle (https://pypi.org/project/wiggle/)
This code is just for showing the noise type, for full training data generation for LSTM please refere to next section. 

TO BE DONE: Add .yml conda environment to run the code.

## 01_LSTM-1D-Conv
This folder refers to Chapter 3.2 of the thesis and contains the notebooks to train a LSTM-NN to perform a noise-free convolution, Equation 3.1 in the thesis. 
In order to run the codes you will need an environment with: numpy, scipy, matplotlib and Tensorflow (PyTorch version is in preparation). 
There are two notebooks in this repository:
  - 00_maxPhase-conv referes to the maximum phase convolution task
  - 01_0Phase-conv.ipynb referes to the zero phase convolution task
It is interesting to notice the importance of the Bi-Directional wrapper in these two examples.


TO BE DONE: Add .yml conda environment to run the code.
