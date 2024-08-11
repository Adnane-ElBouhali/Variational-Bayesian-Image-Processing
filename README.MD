# Variational and Bayesian Methods for Image Processing

This repository contains the practical work completed as part of the IMA203 course "Méthodes variationelles et bayésiennes et optimisation discrète" (Variational and Bayesian Methods and Discrete Optimization) at Télécom Paris.

## Course Overview

This course introduces variational and Bayesian methods for image filtering and segmentation, with a particular focus on optimization techniques. Applications from digital photography, aerial imaging, and medical imaging illustrate the utility of these approaches.

Key concepts covered:
- Variational methods
- Bayesian methods and Markov Random Fields
- Discrete optimization using graph cuts
- Graph models in image processing

## Practical Works

The repository includes five practical works (TPs) that explore various aspects of the course:

1. **Markovian Models and Gibbs Sampling**
   - Introduction to Markov Random Fields
   - Implementation of the Gibbs sampler algorithm
   - Study of the Ising model

2. **Bayesian Analysis with MRF**
   - Binary classification of grayscale images using Markovian models
   - Analysis of gray level distributions
   - Implementation of the ICM (Iterated Conditional Modes) algorithm
   - Optimization using simulated annealing

3. **Graph-cut Optimization (Binary Case)**
   - Implementation of graph-cut algorithms for binary image segmentation

4. **Graph-cut Optimization (Multi-classes)**
   - Extension of graph-cut techniques to multi-class segmentation problems

5. **Variational Methods - Total Variation**
   - Exploration of variational methods for image restoration
   - Implementation of total variation regularization
   - Comparison of quadratic regularization and total variation

Each practical work includes Jupyter notebooks with implementation details and analysis.

## Technologies Used

- Python
- NumPy: For numerical computing and array operations
- Matplotlib: For creating visualizations and plots
- SciPy: Specifically ndimage for image processing tasks
- ImageIO: For reading and writing image files
- scikit-image (skimage): For additional image processing capabilities
- Random: For generating random numbers
- Math: For mathematical operations
- Platform: For getting information about the Python implementation
- Tempfile and OS: For handling temporary files and operating system operations

## Acknowledgements

These practical works were completed as part of the IMA203 course at Télécom Paris. Special thanks to the course instructors for their guidance and support throughout the semester.