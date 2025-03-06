# lsml25
Notebooks for the [2025 PSL Week course on Large Scale Machine Learning](https://cazencott.info/index.php/pages/LSML-25%3A-Large-Scale-Machine-Learning)

## Day 1: Introduction to large scale ML
Work on notebook `1_sklearn_at_scale.ipynb`. 

## Day 2: Deep Learning, AutoEncoders and GANs
* If you have never trained convolutional neural networks on `keras`, start with notebook `2a_beginners_cnn.ipynb`. to train a LeNet Deep Convolutional Network on MNIST. 
* Practice transfer-learning using a standard ConvNet pre-trained on ImageNet with [this notebook 2b](https://colab.research.google.com/drive/1SadnM3Hnklj5vQQX9N4gIWNmt_0ITHwo?usp=sharing)
* **Practice unsupervised deep learning with auto-encoders and GAN with [this notebook 2c](https://github.com/JosephGesnouin/Unsup_gener_nets/blob/main/TP_modeles_g%C3%A9n%C3%A9ratifs.ipynb)**

Beginners should work on TP2a (LeNet on MNIST), and then at least begin TP2c (Deep Generative Models)
**Students who have already practised with Deep ConvNets should work essentially on TP2c.** TP2b may be useful only for those who have never practised Transfer Learning.

## Day 3: Natural Language Processing with Recurrent Neural Networks
Work on notebook `3_nlp_embedding_rnn.ipynb`.

## Day 4: Deep reinforcement learning
Work on notebooks `4a_tabular_RL.ipynb` then `4b_deep_RL.ipynb`.

## Day 5: Stochastic gradient descent
Work on notebook `5_stochastic_gradient_descent.ipynb`.  


## Setup
To run the notebooks, you will need Python, [Jupyter](https://jupyter.org/) (either JupyterLab or Jupyter Notebook), and number of Python librairies. The easiest way to install of this is to use [conda](https://docs.conda.io/en/latest/) and set up an environment specific to this course using the file `package_list.yml`. To this end, you can either:
* if you prefer graphical user interfaces: (1) [install Anaconda](https://docs.anaconda.com/anaconda/install/index.html) and (2) follow the instructions under "Importing an environment" [of the tutorial](https://docs.anaconda.com/anaconda/navigator/tutorials/manage-environments/) to import the environment in `package_list.yml`;
* if you prefer the command line: (1) [install conda](https://docs.conda.io/projects/conda/en/latest/user-guide/install/index.html) and (2) use the following instructions in the command line:
```bash
   conda env create -f package_list.yml -n lsml
   conda activate lsml
```

## Course materials
You will find course materials (pdf of slides) on [the course webpage](https://cazencott.info/index.php/pages/LSML-25%3A-Large-Scale-Machine-Learning)
