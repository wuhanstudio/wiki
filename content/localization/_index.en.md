---
title: "Localization"
icon: "ti-location-pin"
description: "Determing the position with respect to the environment."
date: "2020-06-25T23:15:15+00:00"
type: "docs"
math: true
---

Definition of the SLAM problem:

Given:

- The robot's controls
    $$u_{1:T}={u_1, u_2, u_3, ..., u_T}$$
- Observations:
    $$z_{1:T}={z_1, z_2, z_3, ..., z_T}$$
Wanted:

- Map of the environment

- Path of the robot 
    $$x_{0:T}={x_0, x_1, x_2, x_T}$$

Estimating the robot's location.
