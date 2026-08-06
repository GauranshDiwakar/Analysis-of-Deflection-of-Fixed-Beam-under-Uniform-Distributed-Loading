# ISMB 200 Beam Analysis under UDL — Ansys Mechanical FEA

Finite Element Analysis of an ISMB 200 structural steel beam (6 m span) subjected to a uniformly distributed load of 400 N, performed in Ansys Mechanical. Covers meshing, boundary conditions, deflection, and bending stress results, cross-checked against theoretical calculations.

## 📋 Project Overview

| Parameter | Value |
|---|---|
| Beam Section | ISMB 200 |
| Length / Span | 6 m |
| Load Type | Uniformly Distributed Load (UDL) |
| Total Load | 400 N |
| Material | Structural Steel |
| Analysis Tool | Ansys Mechanical |

## 🎯 Objective

To evaluate the structural behavior of an ISMB 200 beam under a uniformly distributed load by determining:
- Maximum deflection
- Strain distribution along the beam
- Stress distribution along the beam

## 🛠️ Methodology

1. **Geometry** — ISMB 200 cross-section modeled/imported for a 6 m beam length.
2. **Material Properties** — Structural steel properties assigned (Young's Modulus, Poisson's Ratio, Density).
3. **Meshing** — Mesh generated with appropriate element size for convergence.
4. **Boundary Conditions** — Supports applied (e.g., simply supported) and 400 N UDL applied across the span.
5. **Solution** — Static structural analysis solved in Ansys Mechanical.
6. **Post-Processing** — Deflection and stress contour plots extracted.

## 📊 Results

| Result | FEA (Ansys) | Theoretical | % Difference |
|---|---|---|---|
| Max. Deflection | *4.7187e-005* | *TBD* | *TBD* |

*(Replace with your actual computed values)*

## 🖼️ Screenshots

Add images of:
- Meshed model
- Total deformation contour
[Image](https://github.com/user-attachments/assets/0be7c5b1-1ffd-4f4e-86f7-d4b8ec1c30b0)
- Equivalent (von-Mises) stress contour
[Image](https://github.com/user-attachments/assets/116d472d-8ddd-48db-9050-3ed476f81691)

```
/images/deformation.png
/images/stress.png
```

## ✅ Validation

Results obtained from Ansys Mechanical were cross-verified using standard simply-supported beam theory (Euler-Bernoulli beam equations) to confirm accuracy of the FEA model.

## 🧰 Tools Used

- Ansys Mechanical (Static Structural)
- SolidWorks (for CAD Design of Geometry)

## 👤 Author

**Gauransh Diwakar**
B.Tech Mechanical Engineering, IIT Guwahati
