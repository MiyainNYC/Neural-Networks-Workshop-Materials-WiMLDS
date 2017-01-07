# Neural Networks Workshop Materials WiMLDS

Materials for Neural Networks Workshop
* January 21 2017
* NYC Women in Machine Learning &amp; Data Science Meetup

## Installation

### Basic

```shell
git clone https://github.com/lgraesser/Neural-Networks-Workshop-Materials-WiMLDS.git
cd Neural-Networks-Workshop-Materials-WiMLDS
python setup.py install
python test/test_install.py
```

### Tensorflow

Keras is installed with Theano as the backend. If you would like to install Tensorflor then [choose the correct binary to install from TF.](https://www.tensorflow.org/versions/r0.11/get_started/os_setup.html#pip-installation)

```shell
# for example, TF for Python3, MacOS, CPU only
export TF_BINARY_URL=https://storage.googleapis.com/tensorflow/mac/cpu/tensorflow-0.11.0-py3-none-any.whl
# or, TF for Python2, MacOS, CPU only
export TF_BINARY_URL=https://storage.googleapis.com/tensorflow/mac/cpu/tensorflow-0.11.0rc1-py2-none-any.whl
# or Linux CPU-only, Python3.5
export TF_BINARY_URL=https://storage.googleapis.com/tensorflow/linux/cpu/tensorflow-0.11.0rc1-cp35-cp35m-linux_x86_64.whl
# Then install Tensorflow
# Python 2
$ sudo pip install --upgrade $TF_BINARY_URL
# Python 3
$ sudo pip3 install --upgrade $TF_BINARY_UR
```
Then you will need to [change Keras' backend](https://keras.io/backend/) to Tensorflow

## Usage

There are two scripts which can be run through either the ipython notebook or the command line
* Part1/KerasIntro_Example1.py/ipynb
* Part1/KerasIntro_OtherExamples.py/ipynb

The last script is only available with the ipython notebook
* Part2/IntrotoNeuralNets2_CIFAR_2classes.ipynb

Scripts can be run using an ipython notebook or the command line
```shell
# To load ipython notebook
ipython notebook
# Otherwise to run from command line, for example
python Part1/KerasIntro_Example1.py
```

## Going further

* Read Michael Nielson's excellent book [Neural Networks and Deep Learning](http://neuralnetworksanddeeplearning.com/)
* Implement your own neural network. [See my implementation in Python](https://github.com/lgraesser/NeuralNetwork) for an example.
* Check out [my blog](https://learningmachinelearning.org/) for links to more resources on neural networks. I update it on a regular basis.
