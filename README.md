# SysBio 2026: Deep Learning

Hello! Here's the code and data to play around with models for the Deep Learning module of the SysBio 2026 course at EMBL-EBI. The coding task involves inferring transcription sequence motifs from experimental data. This is an adaptation of the tutorial orginally from [A primer on deep learning in genomics](https://www.nature.com/articles/s41588-018-0295-5). Key changes include switching from TensorFlow to PyTorch to illustrate the weeds of how models are trained, and adding linear and multi-layer perceptron models for comparison.

## How to
- Install the conda environment in `environment.yml` using conda or mamba (skip this if you're using a virtual machine)
- Activate the environment and launch `jupyterlab` in the terminal (skip this if you're using a virtual machine)
- Run the notebook `CNN_motif_pytorch.ipynb`

## Learning goals
- How convolutional neural networks and multi-layer perceptrons are defined in PyTorch
- What model training involves
- Examine what convolutional networks learn after training
- Compare performance of different models at predicting TF binding and motif detection
