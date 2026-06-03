# ⚡ Relativistic — Special Relativity Visualizer

An interactive, browser-based visualizer for **Special Relativity** — built with pure HTML, CSS, and JavaScript. No frameworks. No dependencies. Just physics.

![Preview](preview.png)

---

## 🚀 Live Demo

> Open `index.html` in any modern browser. That's it.

---

## 🔭 Features

| Module | Description |
|---|---|
| **Master Velocity Slider** | Drag v from 0 → 0.9999c. All effects update in real time. |
| **Time Dilation** | Computes dilated time, clock rate via γ |
| **Length Contraction** | Animated bar showing rest vs. contracted length |
| **Relativistic Momentum & Energy** | p = γm₀v, KE, total energy E = γm₀c² |
| **Minkowski Spacetime Diagram** | Worldlines, light cone, simultaneity lines, event points |
| **Lorentz Transformation Grid** | Live axis shear of S → S' frame under boost |
| **Light Cone & Causality** | Future/past/spacelike regions with moving worldline |
| **Twin Paradox Calculator** | Input v and Earth time → compute differential aging |

---

## 🧮 Physics Equations Implemented

```
Lorentz factor:       γ = 1 / √(1 − v²/c²)

Time dilation:        Δt' = γ · Δt

Length contraction:   L' = L₀ / γ

Relativistic momentum: p = γm₀v

Total energy:         E = γm₀c²

Lorentz transform:    x' = γ(x − vt)
                      t' = γ(t − vx/c²)

Spacetime interval:   s² = c²Δt² − Δx²  (invariant)

Twin paradox:         τ = T · √(1 − v²/c²)
```

---

## 📂 Project Structure

```
special-relativity-visualizer/
├── index.html       # Everything — self-contained single file
└── README.md
```

---

## 🛠 How to Run

```bash
git clone https://github.com/YOUR_USERNAME/special-relativity-visualizer
cd special-relativity-visualizer
open index.html      # macOS
# or just double-click index.html on Windows/Linux
```

No npm. No build step. No install. Pure physics.

---

## 🎓 Background

Special relativity, introduced by Einstein in 1905, fundamentally changed our understanding of space and time. The key insight: the laws of physics are identical in all inertial reference frames, and the speed of light `c` is constant for all observers.

This leads to counterintuitive consequences:

- **Time dilation** — a moving clock ticks slower
- **Length contraction** — a moving object appears shorter along its direction of motion
- **Relativity of simultaneity** — events simultaneous in one frame are not simultaneous in another
- **Mass-energy equivalence** — E = mc² (rest energy), E = γmc² (total energy)

The **Minkowski diagram** (spacetime diagram) is the standard geometric representation, where time and space are treated as a unified 4D manifold.

---

## 📈 The Lorentz Factor γ

| v/c | γ |
|-----|---|
| 0.0 | 1.000 |
| 0.5 | 1.155 |
| 0.8 | 1.667 |
| 0.9 | 2.294 |
| 0.99 | 7.089 |
| 0.999 | 22.37 |
| 0.9999 | 70.71 |

As v → c, γ → ∞. This is why no massive object can reach the speed of light — it would require infinite energy.

---

## 🧩 Key Concepts

### Minkowski Diagram
- **Vertical axis**: ct (time × speed of light, so both axes have units of length)
- **Horizontal axis**: x (spatial position)
- **Worldline**: the path of an object through spacetime
- **Light cone**: the 45° boundary — nothing can travel outside it
- **Simultaneity lines**: S' frame x-axis tilts toward light cone as v increases

### Twin Paradox
One twin travels at high velocity and returns younger. This is not a paradox — the traveling twin undergoes acceleration (frame change), breaking the symmetry. The proper time of the traveler is genuinely shorter.

---

## 🔗 References

- Einstein, A. (1905). *Zur Elektrodynamik bewegter Körper*. Annalen der Physik.
- Minkowski, H. (1908). *Raum und Zeit*. Address to the 80th Assembly of German Natural Scientists.
- Taylor, E. F., & Wheeler, J. A. (1992). *Spacetime Physics*. W. H. Freeman.

---

## 📜 License

MIT License — free to use, modify, and distribute.

---

*Built as part of a physics research portfolio. Companion to theoretical work on relativistic mechanics.*
