# Implementation of the Self-Organizing Map (SOM) algorithm.

Implementation of the [Self-Organizing Map][som] (SOM) algorithm. 

This project describes an implementation of Kohonen maps, also knownas Self-Organizing Maps (SOM), and their application on a dataset of hand-written digits.

Kohonen map (or self-organizing map) is an algorithm for unsupervised learning of a lower-dimensional representation of data.  It was proposed originally in Kohonen.  The representation learned by Kohonen’s algorithm consists of a square grid of neurons (henceforth called prototypes), whose vertices’ co-ordinates  are  learned  such  that  the  grid  is  embedded  on  the  hypersurface  on which lays the input data cloud.

[som]: https://en.wikipedia.org/wiki/Self-organizing_map

## Requirements
You can run 

```sh
pip install -r requirements.txt
```
to install the dependencies, or simply check the [requirements][reqs] file for the libraries you need installed.


## Usage
On the terminal, run

```sh
jupyter notebook Kohonen maps on hand-written digits.ipynb
```
for example usage and some experiments on the [MNIST dataset](https://en.wikipedia.org/wiki/MNIST_database).

