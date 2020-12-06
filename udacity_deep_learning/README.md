# Interesting Exercises from the Udacity Deep Learning Nanodegree

- `neural_networks/`
    - `Perceptron.ipynb`
        - A perceptron and its optimization algorithm
        - Dataset: synthetic 100 2D samples with 2 classes
    - `GradientDescend.ipynb`
        - Gradient descend applied to the same dataset as before.
    - `StudentAdmissions.ipynb`
        - Gradient descend applied to a linear model.
        - Dataset: student admission data: 3D data (test result, GPA, class rank percentile), converted to one-hot 6D.
        - One-hot encoding is done in pandas using 2 lines: Rank 0-4 -> rank_i 0/1 for i 1-4