# Deep-Learning-and-Machine-Learning-approach-towards-IDS-for-Smart-Vehicles
Abstract of The Paper

Modern vehicles, including autonomous vehicles and connected vehicles, are increasingly connected to the external world, which enables various functionalities and services. However, the improving connectivity also increases the attack surfaces of the Internet of Vehicles (IoV), causing its vulnerabilities to cyber-threats. Due to the lack of authentication and encryption procedures in vehicular networks, Intrusion Detection Systems (IDSs) are essential approaches to protect modern vehicle systems from network attacks. In this paper, a transfer learning and ensemble learning-based IDS is proposed for IoV systems using convolutional neural networks (CNNs) and hyper-parameter optimization techniques. In the experiments, the proposed IDS has demonstrated over 99.25% detection rates and F1-scores on two well-known public benchmark IoV security datasets: the Car-Hacking dataset and the CICIDS2017 dataset. This shows the effectiveness of the proposed IDS for cyber-attack detection in both intra-vehicle and external vehicular networks.
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
