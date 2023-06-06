
ACDFSL for Hyperspectral Image Classification

This repository contains our research on the innovative application of Attentive Cross-Domain Few-Shot Learning (ACDFSL) in Hyperspectral Image (HSI) Classification. This study specifically tackles the challenging aspect of limited labeled data in various environments.

Our approach, which is unique in its integration of attention mechanisms into few-shot learning models, introduces a deep learning architecture of four convolution blocks incorporating Squeeze-and-Excitation (SE) attention and Residual elements. This strategy marks a significant shift from conventional methodologies.

Requirements

To utilize this repository, the following software requirements must be satisfied:

    CUDA: Version 10.0
    Python: Version 3.7
    PyTorch: Version 1.5
    scikit-learn (sklearn): Version 0.23.2
    numpy: Version 1.19.2

Please make sure to have the specific versions installed to ensure the code runs correctly.

Datasets can be found here:
Target: https://www.ehu.eus/ccwintco/index.php/Hyperspectral_Remote_Sensing_Scenes
Source: https://opendatalab.com/Chikusei_Dataset

An example dataset folder has the following structure:
datasets
├── Chikusei_imdb_128.pickle
├── salinas
│   ├── salinas_corrected.mat
│   └── salinas_gt.mat
└── paviaU
    ├── paviaU_gt.mat
    └── paviaU.mat

Usage

After satisfying the required dependencies, you can execute the script for training and prediction on the Salinas dataset using the following steps:

    Clone this repository on your local machine.
    Navigate to the repository's directory using your terminal.
    Run the Salinas-train-predict.py script by entering the following command in the terminal:

bash

python Salinas-train-predict.py

This command will start the training process using the Salinas dataset and, upon completion, perform predictions. Please ensure that the Salinas dataset is correctly placed in the directory and the path is accurately specified within the Salinas-train-predict.py script.

Feel free to explore the script for understanding the training and prediction process, and adjust any parameters if necessary.
