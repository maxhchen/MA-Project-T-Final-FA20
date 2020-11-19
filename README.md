# Collaborative Filtering

Project T Final for CS 189/289A: Introduction to Machine Learning @ UC Berkeley

We aim to guide students through the Collaborative Filtering approach to recommendation systems. We want to expose students to 2 paradigms for collaborative filtering: nearest neighbor-style heuristic searches and latent space models that tie into matrix decompositions studied in EECS 16B. The assignment will be a Jupyter Notebook focused on constructing recommendations for a specific dataset -- Netflix title recommendations being a classic example. We'll start with the former paradigm connecting it to k-means and the clustering problem and analyze the efficiency and accuracy of this approach before moving on to models. Specifically, we will address the sparsity problem and show how SVD/PCA can be used to approach this problem over various choices of loss function and objective formulation. Lastly, we'll show common approaches and open problems with CF in industry (SGD, cold start issue, etc.).

## Contents

- `documentation`: Slides and notes on Collaborative Filtering
  - Slides: https://bit.ly/MA_Project_T_Final_Slides
  - Notes: TBD
- `code`: Jupyter Notebook assignment for Collaborative Filtering, along with necessary files and scripts
- `assessment`: Sample questions to assess student learning

## Contributors

- Maxwell Chen [(@maxhchen)][maxwell]
- Abinav Routhu [(@abinavcal)][abinav]

[maxwell]: https://github.com/maxhchen
[abinav]: https://github.com/abinavcal

## License

![license](https://img.shields.io/badge/license-MIT-brightgreen)
