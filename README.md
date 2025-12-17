# Computational-Neuroscience-Projects
This repository features a collection of projects exploring neural dynamics, spectral analysis, and stimulus decoding using various computational methods.

## Projects Overview
### 1. Neural Decoding in the Allen Visual Behavior Dataset
Focus: Population decoding and cell-type selectivity in the mouse Primary Visual Cortex (V1). 
Key Aim: Quantifying stimulus identity decoding reliability using population activity.
Methods: Logistic Regression for stimulus decoding, PCA for temporal dynamics, and Event-Triggered Averages (ETA) to distinguish Sst-inhibitory neuron tuning from excitatory populations.
Findings: Established that V1 populations provide a highly reliable code for stimulus identity and demonstrated functional specialization in Sst-inhibitory neurons.

### 2. Seizure Dynamics via Wilson-Cowan Modeling
Focus: Investigating neural stability and the "Edge of Chaos" using dynamical systems theory.
Methodology: Implementation of coupled differential equations (Runge-Kutta method) to model excitatory-inhibitory (E-I) interactions.
Analysis: Transitioned the system from a Stable Fixed Point (healthy state) to a Limit Cycle Attractor (seizure state) by perturbing inhibitory synaptic weights ($w_{EI}$).
Criticality Mapping: Constructed a Bifurcation Diagram to identify the Hopf Bifurcation point where neural stability is lost.

### 3. EEG Spectral Analysis of Alpha Rhythms
Focus: Investigating visual cortex alpha rhythms (8-12 Hz) across eyes-open and eyes-closed states.
Goal: Testing the "cortical idling" hypothesis where alpha power increases during eyes-closed states.
Techniques: Power Spectral Density (PSD) calculation using Welch’s method and T-test statistical verification in MATLAB.
