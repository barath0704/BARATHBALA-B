# Recommendation System

This repository contains implementations of multiple recommendation systems for movies using different approaches and datasets.

## Recommendation Systems Implemented

### Recommendation System 1: Graph-Based Collaborative Filtering Model
**Description:**  This model uses a graph-based approach to represent user-movie interactions as a bipartite graph and recommends movies using techniques like graph embedding and random walks.

**Dataset:** Movielens 100k dataset.

**Features:**

1.Data Loading and Preprocessing: Load and preprocess MovieLens 100k dataset for user-movie interactions.

2.Graph Construction: Represent user-movie interactions as a bipartite graph using NetworkX.

3.Graph Embedding: Apply graph embedding techniques (e.g., Node2Vec) to learn low-dimensional embeddings for users and movies.

4.Random Walks and Similarity Calculation: Perform random walks on the graph to calculate similarities between nodes.

5.Personalized Recommendations: Provide personalized movie recommendations based on graph-based similarity scores and embeddings.

**Dataset Dependencies:**

pandas,numpy,networkx,node2vec

### Recommendation System 2: Autoencoder-Based Collaborative Filtering Model
**Description:** This model uses autoencoders, a type of neural network, to learn user and movie representations and recommend movies by reconstructing user rating matrices.

 **Dataset:** Movielens 100k dataset.

**Features:**

1.Data Loading and Preprocessing: Load and preprocess MovieLens 100k dataset for user-movie ratings.

2.Autoencoder Construction: Build an autoencoder model using Keras to learn latent representations of users and movies.

3.Model Training: Train the autoencoder model on user rating data to minimize reconstruction error.

4.Reconstruction and Similarity Calculation: Use the trained autoencoder to reconstruct user ratings and calculate similarities between reconstructed ratings.

5.Personalized Recommendations: Provide personalized movie recommendations based on reconstructed ratings and similarities.

**Dataset Dependencies:**

pandas,numpy,tensorflow,keras

### Recommendation System 3: Reinforcement Learning-Based Recommendation Model
Description: This model uses reinforcement learning to recommend movies by learning a policy that maximizes long-term user engagement.

**Dataset:** Movielens 100k dataset.

**Features:**

1.Data Loading and Preprocessing: Load and preprocess MovieLens 100k dataset for user-movie interactions.

2.State Representation: Define states based on user profiles and interaction history.

3.Action Space: Define actions as recommending a set of movies to users.

4.Reward Function: Define a reward function based on user engagement metrics (e.g., ratings, clicks).

5.Policy Learning: Use reinforcement learning algorithms (e.g., Q-learning, Deep Q-Networks) to learn a policy that maximizes long-term rewards.

6.Personalized Recommendations: Provide personalized movie recommendations based on the learned policy.

**Dataset Dependencies:**

pandas,numpy,tensorflow,keras,gym (for reinforcement learning environment)
## Author:
[BARATHBALA B] (https://github.com/barath0704)
