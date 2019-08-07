# Neural Network Tutorial
A tutorial introduction to neural networks, with an eye towards linguistic applications.  The repository contains slides as well as a Jupyter Notebook with a hands-on demonstration of basic techniques in building and training a neural network for a semantic task.

## Setting up your environment

I recommend using `conda` from the Anaconda Distribution: https://www.anaconda.com/.  My instructions are for UNIX systems (OS X and Linux), but Anaconda should make it easy to follow these steps on Windows as well.

Once installed, you can execute the following:
1. `conda create -n nn-tutorial python=3.7`
2. `conda activate nn-tutorial`
3. `conda install pytorch torchvision jupyter pandas -c pytorch`
4. `conda install plotnine -c conda-forge`
5. `conda install nb_conda_kernels`

### Running the tutorial

It can be helpful to `conda deactivate` from the `nn-tutorial` environment first.  Then:
1. `cd DIR`, where DIR is a directory of your choice
2. `git clone https://github.com/shanest/nn-tutorial.git` 
  1. Alternatively: download the `zip` file from GitHub and extract it to your directory.
3. `conda activate nn-tutorial`
4. `jupyter notebook`

You should now be able to click to open the file `tutorial.ipynb`, and interact with it!
