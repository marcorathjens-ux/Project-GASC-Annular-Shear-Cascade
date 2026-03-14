# 🔄 Math V1.1: Vector-Injection-Return (VIR) & Momentum Loss Analysis

## 1. Energetic Cost of Re-Injection
The adversarial audit (V1.0) correctly identified that re-injecting the processed annular flow into the high-velocity core stream incurs an energy cost. In the GASC system, this is modeled as a momentum loss coefficient $\eta_{VIR}$.

## 2. Dynamic Pressure & Viscous Drag
The energy required to attach the water film via the **Coandă Effect** is subtracted from the residual kinetic energy of the annular stream.

**Loss Equation ($\Delta E_{VIR}$):**
$$\Delta E_{VIR} = \underbrace{f \cdot \frac{L}{d} \cdot \frac{\rho \cdot v_{ret}^2}{2}}_{\text{Viscous wall friction}} + \underbrace{\zeta \cdot \frac{\rho \cdot v_{ret}^2}{2}}_{\text{Curvature/Minor losses}}$$

*   $f$: Darcy friction factor for the injection nozzle.
*   $\zeta$: Resistance coefficient of the Coandă-lip geometry.

## 3. Momentum Balance (Refined)
The resulting velocity $v_{res}$ at the entry of the next module is the weighted sum of the core momentum and the *depleted* return momentum:

$$v_{res} = \frac{\dot{m}_{core} \cdot v_{core} + \eta_{VIR} \cdot (\dot{m}_{ret} \cdot v_{ret} \cdot \cos(\alpha))}{\dot{m}_{total}}$$

**Efficiency Coefficient ($\eta_{VIR}$):**
$$\eta_{VIR} = 1 - \frac{\Delta E_{VIR}}{E_{kin, ret}}$$

*Note: For the 100m simulation (V1.1), $\eta_{VIR}$ is conservatively set to $0.96$ to account for these internal hydrodynamic losses.*

## 4. Boundary Layer Re-Stabilization
Despite the momentum cost, the VIR serves a critical function: It suppresses turbulence at the interface, allowing the subsequent module to operate in a stable, predictable boundary layer $\delta$ earlier than in a free-fall scenario.

---
**Status:** `Hardened-VIR-V1.1`  
**Correction:** `Quantified momentum loss and re-injection energy costs.`
