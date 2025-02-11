---
title: 'DESC: An Open-Source, High-Accuracy Pseudo-Spectral Optimization Code for Stellarators'
authors:
  - name: Yigit Gunsur Elmacioglu
    affiliations:
      - Princeton University
  - name: Dario Panici
    affiliations:
      - Princeton University
  - name: Rory Conlin
    affiliations:
      - University of Maryland
  - name: Daniel Dudt
    affiliations:
      - Thea Energy
  - name: Rahul Gahur
    affiliations:
      - Princeton University
  - name: Kaya Unalmis
    affiliations:
      - Princeton University
license: CC-BY-4.0
exports:
  - format: pdf
    template: ../../template

---

Nuclear fusion offers a clean, sustainable energy solution, eliminating reliance on fossil fuels while overcoming the energy density limitations of other renewable sources. Magnetic confinement fusion, a leading approach to achieving practical fusion, uses electromagnetic forces to confine plasma and counterbalance its internal pressure. Among the two primary device types—tokamaks and stellarators—the latter requires sophisticated numerical optimization due to its lack of inherent symmetry, such as the axisymmetry found in tokamaks. DESC is an open-source pseudo-spectral optimization code tailored for stellarators, utilizing spectral basis functions in all three dimensions to achieve higher accuracy than similar codes. By leveraging JAX’s automatic differentiation, DESC efficiently computes objective function derivatives, while its compatibility with both CPU and GPU architectures enables seamless performance scaling without additional implementation effort. This capability makes DESC highly flexible, enabling seamless integration of diverse physics metrics with minimal implementation effort in Python, thereby advancing stellarator design and optimization. Actively developed and rigorously tested on GitHub using continuous integration (CI), DESC ensures reliability and accessibility for the stellarator optimization community.

# Repository
https://github.com/PlasmaControl/DESC

