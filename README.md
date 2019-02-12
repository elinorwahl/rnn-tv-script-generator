# Recurrent Neural Network TV Script Generator

This is my implementation of a project that constructs a pipeline to process natural language - in this case, scripts from
Moe's Tavern scenes in The Simpsons - and train a recurrent neural network to understand that language and use it to write
new scripts. The original project notebook and requirements, which are part of Udacity's current Deep Learning course,
can be found [here](https://github.com/udacity/deep-learning), in the '[tv-script-generation](https://github.com/udacity/deep-learning/tree/master/tv-script-generation)' folder.

A recurrent neural network is an artificial neural network in which the connections between nodes form a sequence, which
allow the network to store and process information along a sequence of time. This kind of temporal memory is extremely 
useful for recognizing patterns in things like moving images, and written and spoken language - the network can be trained 
to understand how gestures or words unfold from one to the next, and can learn to predict what comes after a particular
word or gesture based on context.

### Usage

Clone the repository and navigate to the downloaded folder:
```
git clone https://github.com/elinorwahl/rnn-tv-script-generator.git
cd rnn-tv-script-generator
```

Using a GPU to run this project is strongly recommended. If you plan to install TensorFlow with GPU support on your local 
machine, follow [this guide](https://www.tensorflow.org/install/) to install the necessary NVIDIA software on your system.
Some alternatives for web-hosted GPU use are [Amazon AWS](https://aws.amazon.com/hpc/) and [Crestle](https://www.crestle.com).
