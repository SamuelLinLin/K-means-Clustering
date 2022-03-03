# Earthquake Project
Project: https://samuellinlin.github.io/Earthquakes/


This project is about sorting a map of earthquakes into n sections. Each section has a centroid. Each section’s locations are closest to the centroid in each section. K-means clustering is a method to sort a group of items into k clusters. Each item in each cluster is closest to the centroid of each cluster. I used k-means clustering to first make k random points as centroids. I then sorted the items into clusters of items closest to each centroid. I then moved each centroid to the average of each cluster. I repeated until there is no difference between the last runs cluster or until the maximum runtime is reached. Because the Earthquake magnitudes are different, I made a new code so that each Earthquake does not impact the new centroid the same. Earthquakes with a higher magnitude would affect the new centroid more.


