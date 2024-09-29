Name: Shanmitha Gopinath
Register Number : 22MIS1203


Self-Organizing Map (SOM) for Wine Quality Dataset
The dataset used is the **Wine Quality Dataset** from the UCI Machine Learning Repository, consisting of various chemical properties of wine (such as alcohol, acidity, etc.) and a quality score (from 0 to 10).
https://archive.ics.uci.edu/dataset/186/wine+quality

This project applies a Self-Organizing Map (SOM) to the wine quality dataset to visualize patterns in the data and cluster wines based on their chemical composition.

The project is made using python. It also requires and utilizes python packages like
- 'minisom' for the SOM implementation
- 'numpy' for numerical operations
- 'matplotlib' for plotting
- 'scikit-learn' for K-Means clustering

Shown:
Distance Map (U-Matrix): Shows the similarity between neighboring neurons.
Hit Map: Displays how frequently each neuron is hit by the data.
Component Planes: Show how individual features vary across the SOM.
K-Means Clustering Circles: Highlights clusters of similar neurons using K-Means.
