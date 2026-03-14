# 📐 Math: GASC Unit Geometry & Tesla Dynamics

## 1. Primary Shear Properties
The foundation of the GASC system relies on the selective extraction of kinetic energy from the turbulent boundary layer $\delta$.

**Shear Ratio ($\sigma$):**
$$\sigma = 1 - \left(1 - \frac{\delta}{R}\right)^2$$
*Definition:* The fraction of the annular mass flow relative to the total flow.

**Boundary Layer Thickness ($\delta$):**
$$\delta(x) \approx 0.37 \cdot x \cdot \left(\frac{\rho \cdot v \cdot x}{\mu}\right)^{-1/5}$$
*Context:* Determines the radial depth of the Hyperbolic Shearing Blade ($HSB$).

---

## 2. Energy Conversion Dynamics
The theoretical power $P_{mod}$ extracts the momentum from the peripheral zone without significantly decelerating the core stream $v_{core}$.

**Power Equation:**
$$P_{mod} = \frac{1}{2} \cdot \sigma \cdot \dot{m} \cdot v^2 \cdot \eta_{visc}$$

**Cascade Conservation Law:**
$$v_{n+1} = \sqrt{v_n^2 \cdot (1 - \sigma) + 2 \cdot g \cdot \Delta h_{module}}$$
*Innovation:* Gravitational pull compensates for the extracted shear energy between modules.

---

## 3. Optimal Tesla Geometry (Disc Spacing)
The disc spacing $h$ must be calculated adaptively to the local flow velocity $v$ to maximize viscous coupling.

**Adaptive Spacing ($h_{opt}$):**
$$h_{opt}(v) \approx k \cdot \sqrt{\frac{\mu \cdot L}{\rho \cdot v}}$$


| Velocity ($v$) | Opt. Spacing ($h$) | Cascade Position |
| :--- | :--- | :--- |
| $2 - 5 \, \text{m/s}$ | $\approx 1.2 \, \text{mm}$ | Upper Section |
| $10 - 15 \, \text{m/s}$ | $\approx 0.8 \, \text{mm}$ | Middle Section |
| $> 20 \, \text{m/s}$ | $\approx 0.4 \, \text{mm}$ | Lower Section |


