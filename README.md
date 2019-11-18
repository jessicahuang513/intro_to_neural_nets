# Introduction to Neural Networks

This tutorial was presented at the QMI General Meeting on November 11, 2019. It covers:

- Neurons
  - Weights
  - Activation Functions
  - Backpropagation
- Single layer Perceptron
- Multilayer Perceptron
- Convolutional Neural Networks

## Setup

1. Clone the git repo:

   1. ```bash
      git clone https://github.com/jessicahuang513/intro_to_neural_nets.git
      ```

2. Go into the intro_to_ml folder, make a virtual environment

   1. ```bash
      cd intro_to_neural_nets
      virtualenv keras-env
      ```

3. Activate virtual environment:

   1. On MacOS

      1. ```bash
         source keras-env/bin/activate
         ```

   2. On Windows

      1. ```bash
         \env\Scripts\activate
         ```

4. Install virtual environment into jupyter notebook:

   1. ```bash
      python -m ipykernel install --user --name=keras-env
      ```

5. Install required packages:

   1. ```bash
      pip install requirements.txt
      ```

6. Start jupyter notebook and open the Neural Networks Tutorial .ipynb file. Change the kernel to keras-env.

