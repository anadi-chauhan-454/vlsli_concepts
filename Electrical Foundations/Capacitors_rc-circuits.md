# Capacitor
A capacitor is a **two-terminal passive device** that stores energy in the form of an electric field.

It consists of:
- two conducting plates  
- separated by an insulating material (dielectric)

## Structure

- Plates → store charge  
- Dielectric → prevents current flow  

\[
C = (epsilon *A)/d
\]

Where:

- \(C\) = capacitance  
- \(epsilon\) = permittivity  
- \(A\) = plate area  
- \(d\) = distance between plates  

---

## Charge-Voltage Relation

\[
Q = C / V
\]

---

## Current-Voltage Relation

\[
I = C *(dV/dt)
\]

👉 Important Insight:  
A capacitor allows current **only when voltage is changing**.

---

## Energy Stored

\[
E = (C * V^2)/2
\]

---

## Behavior

| Condition | Behavior |
|----------|--------|
| DC steady state | acts like open circuit |
| changing voltage | allows current |
| AC signals | passes signals |

---

## Types of Capacitors

### Non-Polarized
- can be connected in any direction  

### Polarized
- must be connected correctly  
- wrong connection → damage/explosion  

---

# 2. RC Circuit

An RC circuit contains:

- Resistor (R)  
- Capacitor (C)  

Used for **timing, filtering, and signal shaping**.

---

# Charging of Capacitor

When connected to a voltage source:

\[
V(t) = V_0 (1 - e^{-t/RC} \right)
\]

\[
I(t) = \frac{V_0}{R} e^{-t/RC}
\]

---

# Discharging of Capacitor

When capacitor releases energy:

\[
V(t) = V_0 e^{-t/RC}
\]

\[
I(t) = -\frac{V_0}{R} e^{-t/RC}
\]

---

# Time Constant (Very Important)

\[
\tau = RC
\]

- After time \(t = \tau\) → capacitor charges to ~63%  
- After \(5\tau\) → almost fully charged (~99%)

---

# Why RC Circuits Matter (Very Important for VLSI)

RC circuits directly relate to:

- signal delay  
- propagation delay  
- rise/fall time  
- clock timing  

# Applications

- filters (low-pass, high-pass)  
- timing circuits  
- noise removal  
- memory elements  
- analog signal processing  

---

# Key Insights

- capacitor stores energy, not current  
- current exists only during voltage change  
- RC determines **speed of circuits**  
- larger RC → slower response  

---

# Summary

| Concept | Meaning |
|--------|--------|
| Capacitor | stores energy in electric field |
| Q = CV | charge-voltage relation |
| I = C * (dV/dt) | current relation |
| RC | determines timing behavior |

