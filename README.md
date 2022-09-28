# Deep-Learning-and-Machine-Learning-approach-towards-IDS-for-Smart-Vehicles
Abstract of The Paper

Modern automobiles, particularly connected and autonomous vehicles, are more and more interconnected to the outside world, enabling a range of functionality and services.The Internet of Vehicles (IoV) is more vulnerable to cyber threats as a result of its increased attack surfaces due to connectivity improvements.The absence of authentication and encryption protocols in automotive networks makes intrusion detection systems (IDSs) crucial defences against network intrusions for contemporary vehicle systems.Convolutional neural networks (CNNs), ensemble learning, and hyper-parameter optimization approaches are used in this paper to present an IDS for IoV systems that is based on transfer learning and ensemble learning.The Car-Hacking dataset and the CICIDS2017 dataset, two well-known public benchmark IoV security datasets, were used in the trials to show that the proposed IDS has over 99.25% detection rates and F1-scores.This demonstrates its potency.This demonstrates how well the suggested IDS works to identify cyberattacks in both internal and external vehicular networks. 
Implementation
CNN Models

    VGG16
    VGG19
    Xception
    Inception
    Resnet
    InceptionResnet

Ensemble Learning Models

    Bagging
    Probability Averaging
    Concatenation

Hyperparameter Optimization Methods

    Random Search (RS)
    Bayesian Optimization - Tree Parzen Estimator(BO-TPE)

Dataset

    CAN-intrusion/Car-Hacking dataset, a benchmark network security dataset for intra-vehicle intrusion detection

    Publicly available at: https://ocslab.hksecurity.net/Datasets/CAN-intrusion-dataset
    Can be processed using the same code

    CICIDS2017 dataset, a popular network traffic dataset for intrusion detection problems

    Publicly available at: https://www.unb.ca/cic/datasets/ids-2017.html

For the purpose of displaying the experimental results in Jupyter Notebook, the sampled subset of the CAN-intrusion dataset is used in the sample code. The subsets are in the "data" folder.
Code

    1-Data_pre-processing_CAN.ipynb: code for data pre-processing and transformation (tabular data to images).
    2-CNN_Model_Development&Hyperparameter Optimization.ipynb: code for the development and CNN models and their hyperparameter optimization.
    3-Ensemble_Models-CAN.ipynb: code for the construction of three ensemble learning techniques.

Libraries

    Python 3.5+
    Keras 2.1.0+
    Tensorflow 1.10.0+
    OpenCV-python
    hyperopt
