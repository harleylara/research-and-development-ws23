# My Action Reading Plan


- [ ] Get familiar with Visual SLAM
    - [ ] A Review of V-SLAM∗
- [ ] Review SLAM performance assessments papers
    - [ ] Introducing SLAMBench, a performance and accuracy benchmarking methodology for SLAM
    - [ ] On measuring the accuracy of SLAM algorithms
    - [ ] Performance Analysis of NDT-based Graph SLAM for Autonomous Vehicle in Diverse Typical Driving Scenarios of Hong Kong
    - [ ] Predicting Performance of SLAM Algorith


## Papers Review

Works on measuring the SLAM performance:
- Dense RGB-D SLAM
    - [Introducing SLAMBench, a performance and accuracy benchmarking methodology for SLAM](./slambench.md)

## SLAM Challenges

before 2006:
- from "Simultaneous Localization and Mapping (SLAM): Part II"
    - nonlinearity
    - data association
    - landmark characterization

## WP 1 - Identify Relevant Metrics for SLAM

Metrics:
- frame rate (slambench)
- energy consumption (slambench)
- Accuracy Trade-Off (slambench)
    - Absolute trajectory error (ATE)

The collection of benchmarks are in my Zotero folder.

## WP 2 - Survey Datasets 

[datasets.yml](./datasets.yml)

- [ICL-NUIM dataset](https://www.doc.ic.ac.uk/~ahanda/VaFRIC/iclnuim.html) (slambench)
    - scale: small
    - environment: indoor
    - type: synthetic
    - sensors: TBD

- [The Victoria Park Dataset](https://www.mrpt.org/Dataset_The_Victoria_Park)
    - scale: large
    - environment: outdoor
    - sensors: TBD
- [Navlab SLAMMOT Datasets](https://www.cs.cmu.edu/~bobwang/datasets.html)
    - scale: large, medium and small
    - environment: outdoor
    - sensors: TBD

- [RADISH Datasets](https://radish.sourceforge.net/): A collection of public datasets
    - scale: large, medium and small
    - environment: indoor and outdoor
    - sensors: N/A
- [OpenSLAM Datasets](https://openslam-org.github.io/): A collection of public datasets and implementations

## WP 3 - Extract Visual Keypoint-based based SLAMs

- Define selection criteria for SLAM implementation selection
- Identify SLAM implementations that meet the selection criteria

Filter for selection:
- Visual Keypoint-based
- Still public in the internet by the author(s)

List of SLAM libraries:
- [CAS Robot Navigation Toolbox](https://openslam-org.github.io/cas-rnt.html)
    - [source code](https://github.com/OpenSLAM-org/openslam_cas-rnt/tree/master)
