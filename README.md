# Inscribed Rectangle Problem

This project explores the **Inscribed Rectangle Problem**, a variation of the famous **Inscribed Square Problem** in topology and geometry. It presents a topological approach to demonstrate that for any Jordan curve, there exists at least one rectangle whose vertices lie on the curve.

## 📘 Background

- **Inscribed Square Problem**: Unsolved in general, it conjectures that every smooth Jordan curve in the plane contains four points that form a square.
- **Inscribed Rectangle Problem**: A more approachable variant which seeks to prove that **a rectangle** (not necessarily a square) can always be inscribed in **any Jordan curve**.

## 🧠 Problem Statement

> Let \( C \) be a Jordan curve (a simple closed curve) in the plane. Prove that there exists a rectangle whose four vertices lie on \( C \).

## 🧩 Approach and Ideas

The proof uses ideas from **topology**, particularly:

- **Unordered pairs of points** on the curve form a **Möbius strip**.
- The Möbius strip is mapped continuously into 3D space such that its boundary maps to the curve \( C \).
- **Borsuk–Ulam Theorem** is used to deduce that there must be two distinct unordered pairs of points on \( C \) that:
  - Have equal-length segments (diagonals).
  - Intersect at the same midpoint.

From this, it follows that such pairs form the diagonals of a rectangle inscribed in \( C \).

## 🔍 Concepts Used

- **Jordan Curves**
- **Möbius Strip Topology**
- **Continuous Mappings**
- **Borsuk–Ulam Theorem**
- **Geometric Symmetry and Parametrization**

## 🖼️ Visual Aids

- 2D to 3D mapping of unordered pairs.
- Möbius strip formation and mapping.
- Examples illustrating the implications of the Borsuk–Ulam theorem.


## 👨‍💻 Author

**Saiyed Mohammad Saihan**  
_Student ID: 21-MT-0427_  
Course: MT-6502 Practical  

## 📜 License

This project is shared for academic purposes. Please cite appropriately if you use this material.

---

Feel free to contribute with improved visualizations, code simulations, or alternative proof ideas!



