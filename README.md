# IterativeClosestPoint
Iterative Closest Point

This is a commonly used algorithm in computer image processing for eliminating error between two sets of point clouds, a source cloud and a fixed cloud. Each iteration of the algorithm computes the nearest neighbor of each source cloud point in the fixed cloud set. The algorithm then determines the optimal rotation and translation for reducing the total distances between the source cloud’s points and their nearest neighbors in the fixed cloud. Once the total distances have been reduced beyond a desired threshold, the rotations and translations of each iteration are totalled.
