# Digital Twin-Ready Acceleration of Production-Scale Wire Laser Additive Manufacturing Using NVIDIA Omniverse

This repository contains supplementary materials for the paper:
**“Digital Twin-Ready Acceleration of Production-Scale Wire Laser Additive Manufacturing Using NVIDIA Omniverse”**  
Main contacts: tomas.jochman@cvut.cz and abdi.mehdi@qhbuild.com.

To obtain source code / the Omniverse Kit application / simulation modules, please contact one of the authors.

## Overview

This work introduces an end-to-end **digital twin-ready simulation framework** for **Wire Laser Additive Manufacturing (WLAM)** that unifies multi-axis robotic execution with physically grounded, **GPU-accelerated process simulation** inside the **NVIDIA Omniverse** ecosystem.

The framework combines two complementary simulation levels:
- **KDDM (Kinematic and Dynamic Deposition Model):** fast, controller-aware prediction of motion-driven deposition artifacts (e.g., effects of blending, acceleration limits, and speed mismatches).
- **MPDM (Multiphysics Deposition Model, based on the Baal Hammon Suite):** high-fidelity simulation of laser–metal interaction and melt-pool physics (including layer stability regimes like balling/blobbing), with extensions toward thermal / thermomechanical prediction.

The digital twin is validated against physical WLAM builds and demonstrated on a production-scale part, where simulation-guided parameter selection enables substantial reductions in build time and operating cost compared to baseline recipes.

## Key Features

- **Omniverse-based digital twin-ready environment:** unified scene, visualization, and simulation workflow leveraging **OpenUSD**.
- **Controller-aware deposition prediction (KDDM):** captures motion-induced defects that CAM/IPW-style verification typically misses.
- **High-fidelity WLAM multiphysics (MPDM / Baal):** ray-traced / multi-reflective laser energy deposition + melt-pool and solidification behavior.
- **GPU acceleration (NVIDIA Warp):** enables interactive or high-throughput simulation loops for parameter exploration.
- **Validation on an industrial WLAM robotic cell:** comparison of predicted vs. observed deposition stability and geometry trends.
- **Production-scale optimization workflow:** demonstrates simulation-driven parameter tuning for higher productivity and improved predictability.

## Promo Video ##
[![Watch the video](https://img.youtube.com/vi/UXpAJiS9Cwg/0.jpg)](https://youtu.be/UXpAJiS9Cwg)

## KDDM Omniverse GUI and Simulation Settings ##
[![Watch the video](https://img.youtube.com/vi/UXpAJiS9Cwg/0.jpg)](https://youtu.be/UXpAJiS9Cwg)

## MPDM Omniverse GUI and Simulation Settings ##
[![Watch the video](https://img.youtube.com/vi/SR7zOOnuDdE/0.jpg)](https://youtu.be/SR7zOOnuDdE)

## Flange KDDM Video ##
[![Watch the video](https://img.youtube.com/vi/w9NGmTFM82Y/0.jpg)](https://youtu.be/w9NGmTFM82Y)

## Flange MPDM Video ##
[![Watch the video](https://img.youtube.com/vi/YYoQza-1N6M/0.jpg)](https://youtu.be/YYoQza-1N6M)

## Cylinder KDDM Video ##
[![Watch the video](https://img.youtube.com/vi/Mo9xvZu_Luw/0.jpg)](https://youtu.be/Mo9xvZu_Luw)

## Screw MPDM Thermomechanics Video ##
[![Watch the video](https://img.youtube.com/vi/DcN99NkuZ_I/0.jpg)](https://youtu.be/DcN99NkuZ_I)

## Images
![Printed part](https://github.com/user-attachments/assets/dc2229cf-39b6-45ea-a47b-146c428bf77c)

## Graphical Abstract
![Graphical Abstract](https://github.com/user-attachments/assets/e0440c7c-0fac-4f93-a6fa-64011c1783eb)
