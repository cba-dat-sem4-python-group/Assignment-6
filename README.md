# Assignment 6
This assignment requires you to work with Facebook network data, data preprocessing and networkx. Note that this is real data from real people!

## Part 1: Preparing data
The dataset you will be working with is available here: https://snap.stanford.edu/data/egonets-Facebook.html

You're first job is to

Download the data  
Unpack the data  
Import the data as an undirected graph in networkx  
This should all be done from your notebook in Python. This is an important step for you to automate data preprocessing.

Note: this could take a while, so if you feel adventurous you can use the multiprocessing library to speed things up.

Hand-in:
- The code for downloading, unpacking and loading the dataset

## Part 2: Analyse the data
Now, let's take a look at the network you imported.

By node degree we mean the number of edges to and from a node. This is different in an undirected network, where in-degree == out-degree, and a directed network where in-degree != out-degree.

By graph degree we mean the number of edges in the entire network.

Hand-in code that display:
- The number of nodes in the network
- The number of edges in the network
- The average degree in the network
- A visualisation of the network inside your notebook

## Part 3: Find the most popular people
We're naturally interested in who has the most friends, so we want to extract top 10. That is, the 10 most connected people.

Hand-in:
- Code that extracts and reports the 10 people with the most connections in the network
