# multi-task-learning-using-oscillating-strategy

## Description

Nowadays, machines are good at doing a single task. However once you train them to do something else, they tend to be very forgetful! Here, we explore one possible method to teach neural networks multiple tricks!

We use the MNIST dataset and our tasks are to recognize two different numbers (in the code 4 and 5) separately. We use an oscillatory training schedule and find that the neural network retains memory of how to do both tasks!

## Usage

Following along the jupyter notebook。
1. oscillating_goals_MNIST.ipynb  

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

Please make sure to update tests as appropriate.

## Future Work

Although this example is very simple, we can hopefully obtain similar results on tasks that differ more greatly. A plausible next step is to make our two tasks completely different data sets such as MNIST and CIFAR10. Maybe eventually we can have a machine that can both recognize speech and have vision and so forth.
