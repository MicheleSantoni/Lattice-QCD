# **Monte Carlo Simulation in QCD**

This repository contains the notebook **`Montecarlo_QCD.ipynb`**, which implements a simple Monte Carlo generator for Quantum Chromodynamics (QCD) processes. The notebook provides a step-by-step demonstration of how to sample physical distributions, compute observables, and visualize results within the QCD framework.

---

## **📌 Overview**

The notebook includes:

* Random generation of events following QCD-motivated probability distributions
* Implementation of probability density functions and kinematic weights
* Use of the acceptance–rejection (hit-or-miss) algorithm
* Simulation of basic QCD observables such as:

  * energy distributions
  * angular distributions
  * invariant-mass distributions
* Visualization of all generated observables using `matplotlib`

This project is intended as an educational tool and a minimal working example of Monte Carlo techniques applied to particle physics.

---

## **🛠 Requirements**

Install the required Python packages:

```bash
pip install numpy matplotlib scipy
```

---

## **▶️ How to Run**

Launch the notebook using Jupyter:

```bash
jupyter notebook Montecarlo_QCD.ipynb
```

or with JupyterLab:

```bash
jupyter lab Montecarlo_QCD.ipynb
```

---

## **📂 Repository Structure**

```
Montecarlo_QCD/
│
├── Montecarlo_QCD.ipynb   # Main notebook
└── README.md              # Project documentation
```

---

## **📊 Output**

The notebook generates:

* Histograms of sampled variables
* Visual comparisons between theoretical and Monte Carlo–generated distributions
* Numerical summaries of the simulation

---

## **🎯 Purpose**

This project demonstrates:

* how Monte Carlo algorithms can be used to model QCD-like processes
* how to sample non-trivial distributions
* how to visualize and interpret generated physical observables

It can be used as a template or baseline for more advanced simulators, such as parton showers or full event generators.

---

## **📄 License**

This project is released under the MIT License. Feel free to use, modify, or extend the code.

---

If you want, I can make a shorter, more formal, more technical, or more visually styled README.
