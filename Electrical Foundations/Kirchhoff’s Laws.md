# Kirchhoff’s Laws

Kirchhoff’s Laws are fundamental rules used to analyze electrical circuits.
They are based on the principles of **conservation of charge** and **conservation of energy**.
# 1. Kirchhoff’s Current Law (KCL)
KCL states:
> The total current entering a node is equal to the total current leaving the node.

## Equation

\[
\sum I_{in} = \sum I_{out}
\]

---

KCL is based on the **conservation of charge**.
Charge cannot accumulate at a node.

---

## Where it used

- node analysis
- digital circuits
- analog circuits
- current distribution problems

---

## Example

If 3A and 2A enter a node:

\[
I_{out} = 5A
\]

---

# 2. Kirchhoff’s Voltage Law (KVL)

## What

KVL states:

> The sum of all voltages in a closed loop is equal to zero.

---

## Equation

\[
\sum V = 0
\]

---

## Why

KVL is based on the **conservation of energy**.

Energy supplied = energy consumed.

---

## Where

- loop analysis
- power circuits
- voltage calculations

---

## Example

In a loop:

\[
10V - 5V - 5V = 0
\]

---

## Key Insight

- Voltage is **conserved in a loop**
- Energy is neither created nor destroyed

---

# Difference Between KCL and KVL

| Law | Based On | Applies To | Conserves |
|-----|--------|-----------|----------|
| KCL | Charge | Node | Current |
| KVL | Energy | Loop | Voltage |

---

# Practical Understanding

- KCL → deals with **current flow at junctions**
- KVL → deals with **voltage around loops**

Both laws are used together to solve circuits.

---

# Applications

- circuit analysis
- nodal analysis
- mesh analysis
- VLSI power distribution understanding

---

# Summary

- KCL ensures **current balance**
- KVL ensures **energy balance**
- Both are essential for analyzing any electrical system

---



