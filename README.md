# ballad-generator

Generates ballads using Deep learning . Using LSTMS and data of some famous ballads . Generates new ballads and autocompletes with initial given texts .

# LSTMs
Long Short-Term Memory (LSTM) networks are a type of recurrent neural network capable of learning order dependence in sequence prediction problems.
This is a behavior required in complex problem domains like machine translation, speech recognition, and more.
LSTMs are a complex area of deep learning. It can be hard to get your hands around what LSTMs are, and how terms like bidirectional and sequence-to-sequence relate to the field.
In this post, you will get insight into LSTMs using the words of research scientists that developed the methods and applied them to new and important problems.
There are few that are better at clearly and precisely articulating both the promise of LSTMs and how they work than the experts that developed them.
We will explore key questions in the field of LSTMs using quotes from the experts, and if you’re interested, you will be able to dive into the original papers from which the quotes were taken.

### Want to run these notebooks on your own machine?

Start by installing [Anaconda](https://www.anaconda.com/distribution/) (or [Miniconda](https://docs.conda.io/en/latest/miniconda.html)), [git](https://git-scm.com/downloads), and if you have a TensorFlow-compatible GPU, install the [GPU driver](https://www.nvidia.com/Download/index.aspx).

Next, clone this project by opening a terminal and typing the following commands (do not type the first `$` signs on each line, they just indicate that these are terminal commands):

    $ git clone https://github.com/deathstar1/ballad-generator.git
    $ cd exploration

If you want to use a GPU, then edit `environment.yml` (or `environment-windows.yml` on Windows) and replace `tensorflow=2.0.0` with `tensorflow-gpu=2.0.0`. Also replace `tensorflow-serving-api==2.0.0` with `tensorflow-serving-api-gpu==2.0.0`.

Next, run the following commands:

    $ conda env create -f environment.yml # or environment-windows.yml on Windows
    $ conda activate tf2
    $ python -m ipykernel install --user --name=python3

Finally, start Jupyter:

    $ jupyter notebook


# Star
If you liked this , do encourage me with Star 个 [Star](https://github.com/deathstar1/ballad-generator) ⭐️ 

# References
https://machinelearningmastery.com/gentle-introduction-long-short-term-memory-networks-experts/
