# Scanner-Generalization Neural Networks (*SGNN*)
* This is the codes for training *SGNN* implemented Python3 with PyTorch framework. It is inspired by domain adaptation [1] with combining weight sparsity control [2] for DNN.
* The task of the *SGNN* is to predict an individual's general psychopathology factor (*p*-factor) based on vectorized resting-state functional connectivity (RSFC) inputs.

Please cite this work as follows:

General psychopathology factor (p-factor) prediction using resting-state functional connectivity and a scanner-generalization neural network, Jinwoo Hong, Jundong Hwang, Jong-HwanLee, Journal of Psychiatric Research (2022), https://doi.org/10.1016/j.jpsychires.2022.12.037

![fig_SGNN_for_GitHub](https://user-images.githubusercontent.com/84111614/148539569-c174a3db-5ffb-4ea5-846d-4218c87b28cf.jpg)

### References
* [1] Ganin, Y., Ustinova, E., Ajakan, H., Germain, P., Larochelle, H., Laviolette, F., ... & Lempitsky, V. (2016). Domain-adversarial training of neural networks. The journal of machine learning research, 17(1), 2096-2030.
* [2] Kim, H. C., Bandettini, P. A., & Lee, J. H. (2019). Deep neural network predicts emotional responses of the human brain from functional magnetic resonance imaging. NeuroImage, 186, 607-627.
