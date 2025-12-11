# Geometry of Learning: Curvature, Orthogonality, and Computational Cost in Neural Networks

A computational study of how **curvature**, **orthogonality**, and **computational complexity** influence optimization behavior in neural networks.  
This project analyzes both theoretical and practical aspects of optimization, from small quadratic models to deep neural networks.

---

## Contents

- Curvature and ill-conditioning (gradient descent vs. Newton vs. conjugate gradient)
- Optimization in shallow neural networks (SGD, L-BFGS, CG)
- Computational limits of second-order methods in deep networks (Hessian size analysis)
- Orthogonality and QR decomposition (effect on gradient descent stability)

---

## Summary

This work demonstrates that:

- Ill-conditioned curvature leads to slow and oscillatory gradient descent.  
- Newton and CG methods converge rapidly in small models due to curvature adjustment.  
- Deep networks make second-order methods impractical because Hessians reach tens of gigabytes.  
- Adam outperforms SGD in deep settings due to adaptive scaling.  
- QR-based orthogonalization reduces gradient oscillation and improves stability.

