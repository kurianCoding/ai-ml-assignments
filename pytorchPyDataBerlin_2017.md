why relu is better than sigmoid?
ai.mulearn.org
##Auto keras
##Feature Extraction

###Resources
Gradcam
fast.ai

## Hyper parameter
parameters that emerge from analysis. Ex: slope, charactersitic of
loss function. Hyper parameters are independent of data

dileep thomas:dilthoms

## PyTorch Berlin 2017

py torch has debugging pydb one can insert stack_trace() and get
control of code during mid-execution.

Keras gives a high level interface:  Keras has more ready made
implementations, but it lacks 

https://cs230-stanford.github.io

## Module
pytorch.NN module is the basic neural network class of pytorch.

## Sequential
One can make a neural network or perceptron by simply creating
a dict, and giving this as input to nn.sequential(), of pytorch module.
This returns a pytorch module, which will sequentially execute the
functinos in the dict in the order of their declaration.

## forward(self,x)
forward is a method of pytorch.nn module, which it executes when
its called to evaluvate its result. It takes as input, itself
and x. Evaluvation of the neural layer/perceptron, returns whatever,
forward method returns

## model loss optimizer
model, optimizer and data can be moved to nvidia gpu in pytorch using the
command .cuda()

model:
optimiser mean square error

## training loop

training loop:
-    train: apply the optimizing function to predict y
-    optimize: find the optimization functions value
-    backward: find the error in input parameters
-    step: find the next set of input parameters(from the corrected)
the training rerpeats until the error reaches within tolerance value
 eval: evaluvate final value

##  transfer learning
 To transfer all the learning from a previous neural net
 to a new neural net. This means replacing the final layer or two with a
 new one, so all the previous learning remains, with only the final
 interpretation changing.
