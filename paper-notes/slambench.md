# Introducing SLAMBench, a performance and accuracy benchmarking methodology for SLAM


## Performace Measurements

- Authors
- Keywords

## Abstract

## Proposed Method

Using KinectFusion as the (only) underlaying algorithm:
- Set of mutiples kernels in C++, CUDA, OpenCL and OpenMP
    - acquire (only CPU)
    - mm2meters
    - bilateralFilter
    - halfSample
    - depth2vertex
    - vertex2normal
    - track
    - reduce
    - solve (only CPU)
    - integrate
    - raycast
    - renderDepth
    - renderTrack
    - renderVolume
- Uses ICL-NUIM dataset for validation
- Metrics:
    - Frame Rate
    - Energy Consumptionk
    - absolute trajectory error (ATE)

## Method(s) for evaluation

The metrics where compare in:
- Multiple hardware platforms
- Multiple software implementations

## Contributions

## Conclusions

## Results

## Challenges

## Personal Notes

- Benefits
    - Only suppport KinectFusion
    - Evaluate over a single dataset
- Discussion compare to other methods
- Open-ended research questions
