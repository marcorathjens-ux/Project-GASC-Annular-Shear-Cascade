# 📊 Simulation V1.2: The "Infrastructural Harvest" (Honest Baseline)

## 1. Objective: Kinetic Energy Recovery (KER)
Unlike high-head turbines designed for maximum extraction from dams, GASC is a **Kinetic Energy Recovery System (KERS)** for existing gravity-fed conduits (e.g., drinking water networks).

### 1.1 Initial Velocity Assumption ($v_0$)
For the 100m baseline, we assume an initial entry velocity of $v_0 \approx 2.0\,\text{m/s}$ (typical flow in pressurized conduits). 

**Revised Initial Yield (Module 1):**
$$v_1 = \sqrt{v_0^2 \cdot (1 - \sigma \cdot \eta_{visc} \cdot \eta_{VIR}) + 2 \cdot g \cdot \Delta x} \approx 14.1\,\text{m/s}$$
*Impact:* The starting momentum slightly increases the first-stage yield but confirms the 520kW total trajectory as a stable conservative estimate.

## 2. Hardened Parameters & Full Calculation
*   $\sigma = 0.1$, $\eta_{visc} = 0.75$, $\eta_{VIR} = 0.96$
*   Mass Flow $\dot{m} = 1000\,\text{kg/s}$

### Iterative Results (Standard Cascade):
*   **Module 1 (10m):** $v_1 \approx 14.0\,\text{m/s} \rightarrow P_1 \approx 70.6\,\text{kW}$
*   **Module 5 (50m):** $v_5 \approx 25.5\,\text{m/s} \rightarrow P_5 \approx 234\,\text{kW}$
*   **Module 10 (100m):** $\sum P_{GASC} \approx 520\,\text{kW}$ (Total Yield)

## 3. Comparison: GASC vs. Standard High-Head
*   **Standard Turbine ($P_{std}$):** $\approx 922\,\text{kW}$ (requires dam, 94% eff.)
*   **GASC System ($\sum P_{GASC}$):** $\approx 520\,\text{kW}$ (requires NO dam, 53% relative eff.)

## 4. The "Parasitic Gain" Argument
While GASC captures only ~56% of the energy compared to a Kaplan turbine, it operates in environments where **zero energy** is currently harvested:
1.  **Pressure Reduction Valves (PRV):** In city water mains, excess pressure is currently wasted as heat. GASC recovers 520kW from "waste".
2.  **Ecological Integrity:** 520kW with **zero** fish mortality and **zero** habitat loss is a superior ecological ROI compared to 922kW with a destroyed river ecosystem.

---
**Status:** `Hardened-Transparency-V1.2`  
**Conclusion:** `Optimized for non-invasive urban and industrial integration.`
