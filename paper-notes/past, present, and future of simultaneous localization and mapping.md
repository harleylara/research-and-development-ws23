# Past, Present, and Future of Simultaneous Localization and Mapping: Toward the Robust-Perception Age

> IEEE TRANSACTIONS ON ROBOTICS, VOL. 32, NO. 6, DECEMBER 2016

## Introduction


SLAM is about: 
- estimation of the state of a robot
- construction of a model (the map) of the environment


The *classical age* of SLAM (1986-2004) was focus on:
- efficiency
- robust data association

The *algorithmic-analysis age* (2004–2015):
- study of fundamental properties of SLAM;
    - observability
    - convergence
    - consistency


About the map: globally consistent representation of the environment, leveraging both ego-motion measurements and loop closures.

In the early days of robotic research odometry suffered drift over time, but the recent odometry algorithms are based on visual and inertial information:
- recent VIO feature small drift. (< 0.5% of the trajectory length) [Onmanifold preintegration for real-time visual–inertial odometry]

The paper proposes that we are entering the third era of SLAM, *robust-perception age* (2016 - present)
- Robust Performance
    - low failure rate for an extended period of time in a broad set of environments
    - fail-safe mechanisms and has self-tuning capabilities
- High-Level Understanding
    - high-level geometry
    - semantics
    - physics
    - affordances
- Resource Awareness
    - available sensing
    - computational resources
- Task-Driven Perception
