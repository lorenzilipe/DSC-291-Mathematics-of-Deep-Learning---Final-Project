# Double-Descent Under Redundant Training Data

This project studies how redundant training data affects double descent in overparameterized regression. Using a fixed random ReLU feature model with a linear teacher, the experiments compare three settings: unique training samples, exact duplicate samples, and near-duplicate samples created with small perturbations.

The main result is that exact duplicates shift the double-descent peak toward the number of unique training samples rather than the total number of rows. Near-duplicates behave differently: they do not move the dominant peak as cleanly, but they significantly worsen conditioning and can create smaller instability bumps before the main interpolation peak.

Overall, the project suggests that redundancy does not always simply reduce sample size. Exact redundancy acts like a reduced constraint count, while approximate redundancy mainly acts like a conditioning problem.

The full project write-up is available here:

[`DSC291 Final Project.pdf`](./DSC291%20Final%20Project.pdf)
