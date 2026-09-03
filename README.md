# Spring-Stiffness
Design, fabrication, and experimental Hooke’s Law validation of a wooden spring testing rig across multiple spring materials
# Experimental Spring Stiffness Test Rig — Hooke's Law & Material Comparison

An experimental mechanics project featuring the design, wooden fabrication, and testing of a dedicated spring-testing apparatus. The rig evaluates the mechanical behavior, elongation characteristics, and spring constants ($k$) of helical tension springs made from different engineering alloys under static loading.

---

## 1. Project Objectives
- Design and construct a rigid, low-cost wooden vertical testing frame equipped with an integrated metric scale.
- Measure axial elongation ($\delta$) under discrete dead loads (10 N to 50 N).
- Compare the compliance and stiffness of **Spring Steel**, **Copper**, and **Aluminum** springs.
- Verify empirical results against theoretical spring calculations derived from Hooke's Law.

---

## 2. Apparatus Design & Fabrication
The test rig was fabricated from seasoned wood to maintain dimensional stability and isolate structural deflection during loading.

- **Vertical Column:** Rigid wooden backplate with an aligned, laser-engraved 300 mm steel metric ruler.
- **Top Mounting Bracket:** Fixed overhang featuring a low-friction hook bolt to eliminate point-load bending moments.
- **Pointer Assembly:** Lightweight horizontal index needle attached to the lower spring hook to permit parallax-free visual readings against the ruler.
- **Loading Mechanism:** Precision calibrated deadweights suspended vertically from a base pan.

---

## 3. Theoretical Framework
According to Hooke’s Law, axial deflection is directly proportional to applied force within the elastic limit:

$$F = k \cdot \delta$$

Where:
- $F$ = Applied Force ($\text{N}$)
- $k$ = Spring Constant / Stiffness ($\text{N/mm}$)
- $\delta$ = Elongation ($\text{mm}$)

For a helical spring, theoretical stiffness is defined by wire geometry and the material's shear modulus ($G$):

$$k = \frac{G \cdot d^4}{8 \cdot D^3 \cdot N_a}$$

- Wire Diameter ($d$): $2.0 \text{ mm}$
- Mean Coil Diameter ($D$): $20.0 \text{ mm}$
- Active Coils ($N_a$): $12$

---

## 4. Experimental Data & Results

### Recorded Deflection Under Static Loading

| Load (N) | Spring Steel ($\delta$, mm) | Copper ($\delta$, mm) | Aluminum ($\delta$, mm) |
| :---: | :---: | :---: | :---: |
| **0**  | 0.0  | 0.0  | 0.0   |
| **10** | 9.8  | 17.5 | 28.6  |
| **20** | 19.5 | 35.1 | 57.1  |
| **30** | 29.4 | 52.8 | 85.9  |
| **40** | 39.1 | 70.2 | 114.3 |
| **50** | 48.8 | 87.9 | 142.9 |

### Force vs. Deflection Response
```text
Load (N)
  50 |                                      * (Al: 142.9 mm)
  40 |                           * (Cu: 70.2 mm)
  30 |                * (Steel: 29.4 mm)
  20 |           *
  10 |      *
   0 +-------------------------------------------------->
     0     20    40    60    80    100   120   140   160  Deflection (mm)
