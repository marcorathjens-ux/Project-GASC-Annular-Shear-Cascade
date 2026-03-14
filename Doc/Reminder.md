# 💡 Project Reminder: Mathematical & Physical Consistency

This document serves as the primary reference for units, fluid properties, and transition thresholds within the **GASC-2030** framework.

## 1. Units & Dimensions
To maintain consistency across all `/math` documentation:

*   **Disc Spacing ($h$):** 
    - Defined in **millimeters (mm)** for hardware specifications.
    - Must be converted to **meters (m)** for all SI-based physical equations.
*   **Velocity ($v$):** Defined in **meters per second (m/s)**.
*   **Mass Flow ($\dot{m}$):** Defined in **kilograms per second (kg/s)**.
*   **Pressure ($P$):** Defined in **Pascal (Pa)** or $N/m^2$.

## 2. Fluid Properties ($H_2O$ at 20°C)
Standard values used for all theoretical simulations:

- **Density ($\rho$):** $\approx 998 \, kg/m^3$
- **Dynamic Viscosity ($\mu$):** $\approx 1.002 \times 10^{-3} \, Pa \cdot s$
- **Kinematic Viscosity ($\nu$):** $\mu / \rho \approx 1.004 \times 10^{-6} \, m^2/s$

## 3. Flow Regime Thresholds
The transition from laminar to turbulent flow significantly impacts the boundary layer thickness $\delta$.

- **Critical Reynolds Number ($Re_{crit}$):** $\approx 5 \times 10^5$ for external flow / flat plates.
- **Pipe Flow Transition:** $\approx 2300$ (Internal diameter based).

*Note: For GASC modules, we primarily operate in the high-velocity turbulent boundary layer regime to maximize kinetic energy availability.*

---
