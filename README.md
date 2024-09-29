Name: Shanmitha Gopinath
Register Number : 22MIS1203


Self-Organizing Map (SOM) for Wine Quality Dataset
The dataset used is the **Wine Quality Dataset** from the UCI Machine Learning Repository, consisting of various chemical properties of wine (such as alcohol, acidity, etc.) and a quality score (from 0 to 10).
https://archive.ics.uci.edu/dataset/186/wine+quality
Features 1-11 as seen in the component planes.
1 - fixed acidity\
2 - volatile acidity\
3 - citric acid\
4 - residual sugar\
5 - chlorides\
6 - free sulfur dioxide\
7 - total sulfur dioxide\
8 - density\
9 - pH\
10 - sulphates\
11 - alcohol\

Column 12 is quality and olumn 13 is wine ID. Both have been excluded while training the SOM.

'swe2011_da2.py' contains the code.
PNGs of outputs are uploaded.
Results explains the observation

This project applies a Self-Organizing Map (SOM) to the wine quality dataset to visualize patterns in the data and cluster wines based on their chemical composition.

The project is made using python. It also requires and utilizes python packages like
- 'minisom' for the SOM implementation
- 'numpy' for numerical operations
- 'matplotlib' for plotting
- 'scikit-learn' for K-Means clustering

Shown:
- Distance Map (U-Matrix): Shows the similarity between neighboring neurons.
- Hit Map: Displays how frequently each neuron is hit by the data.
- Component Planes: Show how individual features vary across the SOM.
- K-Means Clustering Circles: Highlights clusters of similar neurons using K-Means.
