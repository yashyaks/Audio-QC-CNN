# Performance Analysis of Hybrid Quantum-Classical Convolutional Neural Networks for Audio Classification

by
Yash Thakar, Bhuvi Ghosh, Vishma Adeshra, Kriti Srivastava
> The Research focuses on the development of a QC-CNN architecture to perform audio classification using mel-spectrograms. The QC-CNN architecture developed achieved comparative performance with classical models.


## Manuscripts
This paper was presented at the 15th International Conference on Computing Communication and Networking Technologies (ICCCNT), at IIT Mandi and publised in [IEEE Xplore](https://ieeexplore.ieee.org/document/10725668).

DOI: [10.1109/ICCCNT61001.2024.10725668](https://doi.org/10.1109/ICCCNT61001.2024.10725668)

## Abstract

> Audio signals being high-dimensional and complex pose challenges for classical machine learning techniques in terms of computation and generalization on real-world data. This paper evaluates the use of hybrid quantum-classical convolutional neural networks (QC-CNN) that leverage quantum effects like superposition and entanglement for audio classification using mel-spectrograms obtained from audio data. Evaluated on both small-sized and large-sized datasets, the proposed QC-CNN model gave comparable training accuracy with classical CNN (Convolutional Neural Network) on the smaller dataset but outperformed classical CNN on test accuracy (95.04% vs 92.88%) for a larger birdsong dataset and reduced overfitting, thus highlighting the potential advantages of QC-CNNs for audio data. The QC-CNN exhibited higher cross-entropy loss in case of the small-sized dataset which was further significantly reduced when evaluated on the large-sized birdsong dataset. The work demonstrates the application of QC-CNN for audio classification.

## Software implementation

All source code used to generate the results and figures in the paper are in
the `testing` folder.
The calculations and figure generation are all run inside
Jupyter notebooks.
The data used in this study is provided in `testing` folder itself
and the results generated by the code are plotted in `plots.ipynb` notebook.

## Getting the code

You can download a copy of all the files in this repository by cloning the
[git](https://git-scm.com/) repository:

    https://github.com/yashyaks/Audio-QC-CNN.git

## Dependencies

You'll need a working Python environment to run the code.
The recommended way to set up your environment is through the
[virtualenv](https://virtualenv.pypa.io/en/latest/) python package.
The required dependencies are specified in the file `requirements.txt`.
