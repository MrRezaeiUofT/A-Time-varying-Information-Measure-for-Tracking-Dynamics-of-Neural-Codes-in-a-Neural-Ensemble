Here is the complete, polished `README.md` with the citation and all sections properly structured and finalized:

---

```markdown
# A Time-varying Information Measure for Tracking Dynamics of Neural Codes in a Neural Ensemble

This repository contains the MATLAB code accompanying the paper:

**[A Time-Varying Information Measure for Tracking Dynamics of Neural Codes in a Neural Ensemble](https://www.mdpi.com/1099-4300/22/8/880)**  
*Mohammad R. Rezaei, Milos R. Popovic, Milad Lankarany*  
Published in *Entropy*, 2020.

---

## 🧠 Overview

The amount of information carried by differentially correlated spikes in a neural ensemble varies depending on their synchrony. Spikes of different types (synchronous vs. asynchronous) are associated with different stimulus features. 

In this work, we propose a **Time-Varying Entropy (TVE)** measure that quantifies how neural codes evolve over time within an ensemble of neurons. Key findings include:
- **Synchronous and asynchronous spikes** exhibit different entropy profiles and are distinguishable in their probability distributions.
- These spikes encode **different features of the stimulus**, with synchronous spikes reflecting fast components and asynchronous spikes capturing slower variations.
- **TVE** effectively tracks these coding dynamics.
- A **Kalman filter-based decoder** is developed to reconstruct the stimulus, showing that different features of the input signal can be decoded by focusing on different spike types.

---

## 🚀 Usage

### Requirements
- MATLAB (tested on R2018b and later)
- Signal Processing Toolbox
- Statistics and Machine Learning Toolbox

### How to Run
To reproduce the main results:

1. Clone the repository:
   ```bash
   git clone https://github.com/MrRezaeiUofT/A-Time-varying-Information-Measure-for-Tracking-Dynamics-of-Neural-Codes-in-a-Neural-Ensemble.git
   ```

2. Open MATLAB and navigate to the `Code` directory.

3. Run the main script:
   ```matlab
   MainSolution
   ```

This will execute the full pipeline including spike generation, entropy calculation, and stimulus reconstruction.

---

## 📊 Reproducing Results

Scripts for reproducing main figures from the paper can be found in the `Figures/` folder. Paths may need to be updated to point to the appropriate `Data/` and `Results/` folders.

---

## 📄 Citation

If you use this code in your work, please cite the following:

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
```

📄 [Read the Paper](https://www.mdpi.com/1099-4300/22/8/880)

---

## 👨‍🔬 Authors

- **Mohammad R. Rezaei** – [GitHub Profile](https://github.com/MrRezaeiUofT)
- **Milos R. Popovic**
- **Milad Lankarany**

For questions or collaborations, feel free to reach out to [mr.rezaei@mail.utoronto.ca](mailto:mr.rezaei@mail.utoronto.ca)

---

## 📜 License

This project is released under the [MIT License](LICENSE). Feel free to use and adapt for academic and research purposes.
```

---

Let me know if you'd like to also include visual examples (e.g. figure previews) or a `LICENSE` file to go with it.
