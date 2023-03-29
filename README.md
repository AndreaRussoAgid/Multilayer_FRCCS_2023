# Multilayer_FRCCS_2023
Multilayer network with different nodes and edges:

These are some examples of multilayer network creation, starting with the choice of how many words to take, in relation to the Database. 
We chose 300 words per layer because it is a good balance between understanding the text-topic and the technical limit of gefi and the layers for its observation. 


MultiLayer_1K_nodes_for_Layer.pdf:

Multilayer network created by getting the most 10000 words per layer. 
The number of nodes and edges does not help to understand the words-context of the various topics per layer. 
Network with 1549 nodes and 3006 edges.


Layer_90k_nodes.png:

The network created through the use of all nodes and edges of only one layer (that of the round of 16, the smallest) shows a clear difficulty both tenically, because the network overruns the boundaries of the graph, and also a difficulty in understanding the text, in order to understand the context-words of the various topics. 
This is a clear example of the need to limit nodes and edges in order to understand the dynamics of words and topics/contexts. 
The network shows 90K nodes and 200K edges.
