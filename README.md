# Collaborative Filtering

Project T Final for CS 189/289A: Introduction to Machine Learning @ UC Berkeley

## Objectives:
We aim to guide students through the Collaborative Filtering approach to recommendation systems. We want to expose students to 2 paradigms for collaborative filtering: nearest neighbor-style heuristic searches and latent space models that tie into matrix decompositions studied in EECS 16B. The assignment will be a Jupyter Notebook focused on constructing recommendations for a specific dataset -- Netflix title recommendations being a classic example, as well as the MovieLens dataset. We'll start with the former paradigm connecting it to KNN; we will then move on to the models approach, which will address issues with sparsity and show how other techniques -- namely, matrix factorizations similar to Diagonalization/SVD seen in EECS 16AB -- can be used to approach this problem. Lastly, we'll touch upon common approaches for Collaborative Filtering in Industry (Surpriselib, Deep Learning, Regularization), and open problems (e.g. cold start issue).

### Specific Objectives:
- Apply knowledge of Pandas and Numpy to load and analyze novel datasets
- Utilize Pandas, Numpy, and Matplotlib to perform Exploratory Data Analysis (EDA) and understand the layout, information, and biases in a given dataset
- Explore cosine similarity as a measurement of likeness between high-dimensional feature vectors of users and movies
- Connect previous ideas of clustering to apply K-Nearest Neighbors towards grouping similar users or movies
- Draw connections to previous matrix factorizations learned in 16AB, and explore how to use gradient descent to learn latent space embeddings
- Use and appreciate packages used in industry (such as Surpriselib) for Collaborative Filtering

## Contents

- `documentation`: Slides and notes on Collaborative Filtering
  - Google Slides Mirror: https://bit.ly/MA_Project_T_Final_Slides
  - [Slides Link](https://github.com/maxhchen/MA-Project-T-Final-FA20/blob/main/documentation/CollabFilteringSlides.pdf)
  - [Notes](https://github.com/maxhchen/MA-Project-T-Final-FA20/blob/main/documentation/NotesCF.pdf)
- `code`: Jupyter Notebook assignment and solutions for Collaborative Filtering
  - [Student Version](https://github.com/maxhchen/MA-Project-T-Final-FA20/blob/main/code/%5BStudent%20Copy%20%5D%20Collaborative%20Filtering.ipynb)
  - [Solutions](https://github.com/maxhchen/MA-Project-T-Final-FA20/blob/main/code/%5BSolutions%5D%20Collaborative%20Filtering.ipynb)
- `assessment`: Sample questions to assess student learning
  - [Student Version](https://github.com/maxhchen/MA-Project-T-Final-FA20/blob/main/assessment/%5BStudent%20Copy%5D%20189%20Project%20T%20Assessment.pdf)
  - [Solutions](https://github.com/maxhchen/MA-Project-T-Final-FA20/blob/main/assessment/%5BSolutions%5D%20189%20Project%20T%20Assessment.pdf)

## Contributors

- Maxwell Chen [(@maxhchen)][maxwell]
- Abinav Routhu [(@abinavcal)][abinav]

[maxwell]: https://github.com/maxhchen
[abinav]: https://github.com/abinavcal

## License

![license](https://img.shields.io/badge/license-MIT-brightgreen)
