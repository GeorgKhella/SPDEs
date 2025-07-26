# Stochastic Partial Differential Equations (SPDEs)

This repository contains the LaTeX source and supporting materials for the semester project titled **"Stochastic Partial Differential Equations"**, authored by Georg Khella (March 2025). The project provides a rigorous introduction to SPDEs, with a focus on stochastic integration in Hilbert spaces and applications to nonlinear variational problems.

## 📘 Abstract

We develop the theory of stochastic integration in infinite-dimensional Hilbert spaces, focusing on the construction of the Itô integral and its extension to cylindrical Brownian motions. Using this framework, we formulate and prove the well-posedness of a class of nonlinear SPDEs in variational form. The theory is applied to a concrete example involving the 4-Laplacian with additive trace-class noise, and complemented with an energy identity and long-time behavior analysis under stochastic forcing.

## 📂 Structure

The main sections of the project include:

- **Stochastic Integration in Hilbert Spaces**
  - $L^2$ theory and Cauchy sequences
  - Construction of the real-valued and Hilbert-space-valued Itô integral
- **Cylindrical Brownian Motion**
  - Regular representation and spectral decomposition
  - Hilbert–Schmidt operator framework for stochastic integration
- **Well-posedness of SPDEs**
  - Gelfand triples: $V \subset H \subset V^*$
  - Structural assumptions: hemicontinuity, monotonicity, coercivity, boundedness
  - Existence and uniqueness theorem for SPDEs
- **Application to a Nonlinear SPDE**
  - A stochastic evolution equation with 4-Laplacian drift and additive noise
  - Verification of structural assumptions
- **Energy Estimates and Long-Time Behavior**
  - Generalization of Itô's formula to infinite dimensions
  - A priori estimates on $\mathbb{E}[\|X(t)\|_H^2]$ and $\int_0^T \mathbb{E}[\|X(t)\|_V^4] dt$
  - Threshold phenomena under linear damping and multiplicative noise

## 🧠 Mathematical Tools

The project relies on techniques from:

- Functional analysis (Sobolev spaces, duality, reflexivity)
- Stochastic calculus in infinite dimensions
- Variational methods and monotone operator theory
- SPDE theory based on Gelfand triples

## 🔗 References

Key references include works by:

- Liu & Röckner (2015) — _Stochastic PDEs: An Introduction_
- Goodair & Crisan (2024) — _Stochastic Calculus in Infinite Dimensions_
- Brezis, Folland, Reed & Simon — Functional and Real Analysis
- Lecture notes by Fabio Nobile (2024/2025)

Full bibliography is included in the PDF.

## 📄 PDF

The full compiled paper is available as `SemesterProject-GeorgKhella.pdf`.

## ✍️ Author

**Georg Khella**  
MSc Student in Applied Mathematics  
École Polytechnique Fédérale de Lausanne (EPFL)  
Email: [your.email@example.com]

---

**Note**: This project is theoretical in nature and does not include code. If you're interested in numerical schemes or simulations of SPDEs (e.g. finite element methods or Euler–Maruyama in Hilbert space), feel free to open a discussion or fork the repository.
