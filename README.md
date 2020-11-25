# CNN_IPMSM
Part of "Towards End-to-end Deep Learning Analysis of Electrical Machines" project

This project aims to develop DL tools to facilitate high-speed AI-assisted analysis of Electrical Machines.
Specifically, the topics of output curve prediction and optimal DL architectures are studied.

This project contains codes used to train CNNs that predict output torque curves or average torque values.

Preprint of the full text is available at: 
https://www.techrxiv.org/articles/preprint/Towards_End-to-end_Deep_Learning_Analysis_of_Electrical_Machines/13134932/1

Here "CNN_average_torque" file contains codes used to train models on datasets wherein output torques are averaged, i.e. the dimension of every output vector is 1.
"CNN_torque_curves" contains codes used for models trained on datasets that include the complete torque curves, i.e. the dimension of every output vector is 91.

Datasets as Pytorch tensors are available at:
https://data.mendeley.com/datasets/j7bbrmmn4k/1

Dr Nikita Gabdullin, 2020
