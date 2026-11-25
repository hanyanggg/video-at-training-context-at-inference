# Video Distillation at Training, Asymmetric Context at Inference: Accuracy–Cost Trade-offs in Human Pose Estimation

Official repository for **"Video Distillation at Training, Asymmetric Context at Inference: Accuracy–Cost Trade-offs in Human Pose Estimation"**.

## Overview

We study how video should be spent between **training-time distillation** and **inference-time temporal context** in top-down Vision Transformer human pose estimation, analyzing accuracy–compute–latency trade-offs on PoseTrack17 and PoseTrack21.

## Release Plan

- Training and distillation scripts (`B / G / D / U` and `T / T+U`)
- Exact single-frame folding (`U-cont.`) and center-preserving asymmetric inference (`Asym-128 / 192 / 256`)
- End-to-end GPU pipeline profiler with eight-frame decoded-frame caching
- Trained checkpoints and exact PoseTrack21 validation-split manifest

> Full code, checkpoints, and evaluation manifests will be released upon paper acceptance.
