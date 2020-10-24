
{
 "cells": [
  {
   "cell_type": "markdown",
   "metadata": {},
   "source": [
    "# Long-Short Term Memeory\n",
    "\n",
    "Long-short term memeory (LSTM) is a type of recrrent neural network (RNN), which a class of neural networks that is designed to deal with temporal data. The neurons of RNN have a cell state/memory, and input is processed according to this internal state, which is achieved with the help of loops with in the neural network. There are recurring module(s) of ‘tanh’ layers in RNNs that allow them to retain information. However, not for a long time, which is why we need LSTM models.\n",
    "\n",
    "Recurrent Neural Network(RNN) are a type of Neural Network where the output from previous step are fed as input to the current step. Therefore, RNN has memory to remember the previuos state as it estimate the current state. The following figure shows a simple one neuron RNN that uses the following formula:\n",
    "\n",
    "$$ h_t = f(h_{t-1} , x_t) $$\n",
    "\n",
    "where $h_t$ is the current state, $h_{t-1}$ is the previous state, and $x_t$ is the current input as related to time $t$.\n",
    "\n",
    "\n",
    "<img src='RNN.jpg'>\n",
    "\n",
    "\n",
    "> Recurrent :  متكرر او متواتر\n",
    "\n",
    "\n",
    "## LSTM\n",
    "\n",
    "This special kind of RNN can learn long term dependencies as the recurring model has four layer interacting with each other:\n",
    "\n",
    "\n",
    "<img src='lstm.jpg'>\n",
    "\n",
    "Pleae follow:\n",
    "\n",
    "https://colah.github.io/posts/2015-08-Understanding-LSTMs/ \n"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": null,
   "metadata": {},
   "outputs": [],
   "source": []
  }
 ],
 "metadata": {
  "kernelspec": {
   "display_name": "Python 3",
   "language": "python",
   "name": "python3"
  },
  "language_info": {
   "codemirror_mode": {
    "name": "ipython",
    "version": 3
   },
   "file_extension": ".py",
   "mimetype": "text/x-python",
   "name": "python",
   "nbconvert_exporter": "python",
   "pygments_lexer": "ipython3",
   "version": "3.7.6"
  }
 },
 "nbformat": 4,
 "nbformat_minor": 4
}
