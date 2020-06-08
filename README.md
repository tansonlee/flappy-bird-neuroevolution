# flappy-bird-neuroevolution

How the algorithm will work:
1. send out (100) birds
2. calculate the fitness of each bird
3. make a list of all the neural netowrks of the birds where the bird appears more depending on their fitness
4. randomly pick (100) from the list to create a new population
5. mutate all the neural networks
6. send them out an repeat

ml5 - https://mljs.github.io/feedforward-neural-networks/
* simple very basic 4 function neural net

neataptic - https://wagenaartje.github.io/neataptic/docs/neat/
* specific neat library

synaptic - https://towardsdatascience.com/neural-network-plays-flappy-bird-e585b1e49d97
* tutorial by towards datascience
* more complicated
