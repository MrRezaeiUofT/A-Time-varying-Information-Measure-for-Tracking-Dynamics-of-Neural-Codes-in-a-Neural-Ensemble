# A Time-Varying Information Measure for Tracking Dynamics of Neural Codes in a Neural Ensemble

This repository contains the MATLAB code accompanying the paper:

**"A Time-Varying Information Measure for Tracking Dynamics of Neural Codes in a Neural Ensemble"**  
by *Mohammadreza Rezaei, Milos R. Popovic, and Milad Lankarany*  
Published in *Entropy*, 2020.  
📄 [Read the paper](https://www.mdpi.com/1099-4300/22/8/880)

---

## Overview

The amount of information carried by spikes in a neural ensemble depends on their correlation structure. Synchronous and asynchronous spikes convey different aspects of the stimulus and have distinct entropy characteristics.

In this work, we:

- Introduce a **Time-Varying Entropy (TVE)** measure to quantify how information evolves over time in neural populations.
- Apply TVE to a mixed stimulus (slow and fast signals) and demonstrate that synchronous and asynchronous spikes exhibit separable entropy profiles.
- Show that different spike types encode complementary information across different timescales.
- Develop a **Kalman filter-based decoder** to reconstruct stimuli from spike trains.
- Demonstrate that slow and fast components of the stimulus can be reconstructed using asynchronous and synchronous spikes, respectively.

---

## Usage

To run the simulation:

1. Open `MainSolution.m` in MATLAB.
2. Execute the script to reproduce the figures and analysis from the paper.

---

## Citation

If you use this code or reference this work in your research, please cite:

```bibtex
@article{rezaei2020time,
  title={A time-varying information measure for tracking dynamics of neural codes in a neural ensemble},
  author={Rezaei, Mohammad R and Popovic, Milos R and Lankarany, Milad},
  journal={Entropy},
  volume={22},
  number={8},
  pages={880},
  year={2020},
  publisher={MDPI}
}
