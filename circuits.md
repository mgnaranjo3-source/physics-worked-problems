# DC Circuits

| Relationship | Formula |
|---|---|
| Ohm's law | V = I·R |
| Power | P = V·I = I²·R = V²/R |
| Series resistors | R_total = R₁ + R₂ + ... |
| Parallel resistors | 1/R_total = 1/R₁ + 1/R₂ + ... |

---

## Problem 1: single resistor

A 12 V battery is connected to a 4.0 Ω resistor. Find the current and the power dissipated.

- **Current:** I = V/R = 12 / 4.0 = **3.0 A**
- **Power:** P = V·I = 12 × 3.0 = **36 W**
- **Check:** P = V²/R = 144 / 4.0 = 36 W ✓

---

## Problem 2: resistors in series

The same 12 V battery is connected to a 4.0 Ω and a 2.0 Ω resistor in series. Find the current and the voltage across each resistor.

- **Total resistance:** 4.0 + 2.0 = 6.0 Ω
- **Current (same through both):** I = 12 / 6.0 = **2.0 A**
- **Voltages:** V₁ = 2.0 × 4.0 = **8.0 V**; V₂ = 2.0 × 2.0 = **4.0 V**
- **Check:** 8.0 V + 4.0 V = 12 V ✓ (Kirchhoff's voltage law)

---

## Problem 3: resistors in parallel

The 12 V battery is connected to two 4.0 Ω resistors in parallel. Find the total resistance and the total current.

- **Total resistance:** 1/R = 1/4.0 + 1/4.0 = 0.5 → R = **2.0 Ω**
- **Total current:** I = 12 / 2.0 = **6.0 A** (3.0 A through each branch)
- **Check:** each branch has the full 12 V across it: 12 / 4.0 = 3.0 A; 3.0 + 3.0 = 6.0 A ✓
- **Note:** the parallel total (2.0 Ω) is **smaller** than either resistor. If a calculation gives a larger value, it is wrong.
