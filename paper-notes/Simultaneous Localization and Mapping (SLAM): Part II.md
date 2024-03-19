# Simultaneous Localization and Mapping (SLAM): Part II

Year: 2006
Authors: Tim Bailey and Hugh Durrant-Whyte


3 key research areas
- computational complexity. Methods used to address this problem:
    - linear-time state augmentation
    - sparsification in information form
    - partitioned updates
    - submapping
- data association (important for so-called loop-closure problem):
    - batch-validation
    - appearance-based methods
    - multihypothesis techniques
- environment representation:
    - (trend at that time) trend towards richer appearance-based models of landmarks and maps.
    - trajectory estimation
    - landmark estimation

## Computational Complexity

Characterized as:
- optimal: estimates and covariances that are equal to the full-form SLAM
- conservative: larger uncertainty or covariance than the optimal result

1. Re-formulating the:
    - time-update: using `state-augmentation` methods
    - observation-update: `partitioned form` of the update equations
2. Re-formulation of the standard space-space: 
    - using `sparsification` (The resulting algorithms are usually conservative but still yield good estimates)
    - `submapping`: broken map into regions (Submapping techniques generally provide a conservative estimate in the global frame.)
