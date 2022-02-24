# An struggle with Hamiltonian neural networks!

## Summery
HNN is a kind of neural network that obeys the law of conservation of energy, it has a special form of loss function written by the use of the Hamiltonian Equation of the system.

This project is a reimplimanation of "Hamilton Neural Network" article by sam greydanus.
the main project is implimented in pytorch here you can find code in Tensorflow.

Research shows baseline neural network (usual multilayer perceptron(MLP) neural networks) can not show conservation of energy and it will make false predictions but the hamiltonian neural network can understand physics lows (like conservation of energy)  and make corect predictions.

Our results for mass-spring and ideal pendulum can be seen here
they show a good conformity the results of mane article

 ### mass-spring system 
![Test Image 7](https://github.com/kimia-zahed/hamiltonian_neural_network/blob/main/picture_massSpring/hamiltonyPerTime_massSpringHNN.jpg)
![Test Image 7](https://github.com/kimia-zahed/hamiltonian_neural_network/blob/main/picture_massSpring/hamiltonyPerTime_massSpringBaseline.jpg)

Baseline prdiction clearly showes a fall in energy while there is no fraction in model. real system is fluctuating aroud an amount of conserved energy it is predicted verey well by HNN.

![Test Image 7](https://github.com/kimia-zahed/hamiltonian_neural_network/blob/main/picture_massSpring/trajectory_massSpringBaseline.jpg)
![Test Image 7](https://github.com/kimia-zahed/hamiltonian_neural_network/blob/main/picture_massSpring/trajectory_massSpringHNN.jpg)

### ideal pendulum

this time Baseline model predict an increase in energy! while no energy is added.
again real system has fluctuating aroud an amount of conserved energy and it is predicted by HNN.
![Test Image 7](https://github.com/kimia-zahed/hamiltonian_neural_network/blob/main/pictureidealPendulum/hamiltonyPerTime_pendulumBaseline.jpg)
![Test Image 7](https://github.com/kimia-zahed/hamiltonian_neural_network/blob/main/pictureidealPendulum/hamiltonyPerTime_pendulumHNN.jpg)

## How to run

Code will be ran simply in google colab. if you want to run it in personal coumputer you only need to install jupyternote bok and needed libraries. 

### needed libraries
1-Tensorflow and Keras backend Tensorflow
2-scipy
3-autograd
4-pandas
5-matplotlib
6-numpy
