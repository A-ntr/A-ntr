<h1 align="center">An Tran</h1>

<p align="center">
  Python and C++. Data structures, algorithms, and applied machine learning.
</p>

<p align="center">
  <img alt="Python" src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white">
  <img alt="C++" src="https://img.shields.io/badge/C++-00599C?style=flat-square&logo=cplusplus&logoColor=white">
  <img alt="CMake" src="https://img.shields.io/badge/CMake-064F8C?style=flat-square&logo=cmake&logoColor=white">
  <img alt="Git" src="https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white">
</p>

<br>

## About

I'm building a model that gives every flight on tomorrow's schedule a delay-risk tier, and I practice algorithms on NeetCode in Python. My C++ work so far is a self-balancing tree from a data structures course.

## Projects

| Project | What it is | Stack |
| --- | --- | --- |
| [delta-delay-risk](https://github.com/A-ntr/delta-delay-risk) | Night-before delay risk tiers for airline ops planners. The model predicts the probability of a delay over 15 minutes and thresholds it into low, medium, and high. Every feature is knowable the night before, and the train/test split is chronological. In progress. | Python |
| [AVL](https://github.com/A-ntr/AVL) | A custom AVL tree that indexes University of Florida student account records by GatorID. | C++, CMake |

## Right now

I'm writing the historical delay-rate features for `delta-delay-risk`. They fall back from aircraft tail to route to carrier when a flight has little history, so no flight on tomorrow's list goes unscored. Next are the Bureau of Transportation Statistics data pull, an aircraft-age join from the FAA registry, and a baseline XGBoost model.
