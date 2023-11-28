# Influence in Performance of Feature Descriptor and Matching in Visual Keypoint-based Tracking for Simultaneous Localization and Mapping (SLAM)


## Story-telling

- Why is this relevant?
- The importance of SLAM in robotics



- assess the performance provide a clear view of the research direcction

## Workpackages


- Use multiple datasets for assessment 
    - "We furthermore encourage authors to evaluate their algorithms based on multiple datasets and not just using a single in order to illustrate the generality of the method and not being optimized for a single dataset." [On measuring the accuracy of SLAM algorithms]
- Measuring relative error is better then global error 
    - "This overcomes serious shortcomings of approaches using a global reference frame to compute the error." [On measuring the accuracy of SLAM algorithms]

Harley's notes:
- How to measure runtime if less features would be faster but not necesaryly better ?

## Keywords

*check diagram*

## Related works

Proposed approach(s):
Method(s) for evaluating approach:
Contributions:
Conclusions:
Results:
Challenges (in the scope of work):

----------------------------------------
## Detector, matching and SLAM

### [A review of feature detection and match algorithms for localization and mapping]

Proposed approach(s):
- None

Method(s) for evaluating approach:
- experiments on their accuracy, speed, scale invariance and rotation invariance.
- scale invariance: Number of correct matches between images in different scale (more is better)
- rotation invariance: Number of correct matches between images at different orientation (more is better)
- speed: runtime from feature detection, description to match (less is better)

Contributions:
- no notable contribution

Conclusions:
- ORB is faster at the cost of the number of correct matches
- SIFT is slower but more correct in matching

Results:
- ORB is the x10 faster than SURF and x40 faster than SIFT in detecting and matching features
- SIFT most correct matching and better accuracy (they did not measure accuracy in the paper)

Challenges (in the scope of work):
- None

Personal notes:
- Fail to assess the detection and matching for SLAM

### [Features detection and matching for visual simultaneous localization and mapping (VSLAM)]

Proposed approach(s):
Method(s) for evaluating approach:
- dataset: feature detectors were evaluated using dataset provided by the Robotics Research Group at University of Oxford.

Contributions:
Conclusions:
Results:
Challenges (in the scope of work):

Personal notes:
- Fail to assess the detection and matching for SLAM

----------------------------------------
Descriptors and matching:
- [Analysis and Evaluation of Keypoint Descriptors for Image Matching]
- [Feature Matching Performance of Compact Descriptors for Visual Search]
- [Image Matching Using SIFT, SURF, BRIEF and ORB: Performance Comparison for Distorted Images]

Detector, descriptor and matching:
- [Evaluation of local detectors and descriptors for fast feature matching]

Detectors and descriptors:
- [Analysis of feature detector and descriptor combinations with a localization experiment for various performance metrics]
- [Performance Assessment of Feature Detector-Descriptor Combination]

Only descriptors:
- [A Comprehensive Performance Evaluation of 3D Local Feature Descriptors]
- [A performance evaluation of local descriptors]

Detectors, Descriptors and SLAM
- [A Comparison of Feature Detectors and Descriptors in RGB-D SLAM Methods]

Descriptors and SLAM
- [A comparison of feature descriptors for visual SLAM]

Specifics:
- [A fast local descriptor for dense matching]


Others that may be relevant:
- [LightGlue: Local Feature Matching at Light Speed]
- [SuperGlue: Learning Feature Matching with Graph Neural Networks]

