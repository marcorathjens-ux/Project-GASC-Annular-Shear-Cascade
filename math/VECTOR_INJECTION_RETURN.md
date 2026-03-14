# 🔄 Math: Vector-Injection-Return (VIR) & Coandă-Stabilization

## 1. The Physical Challenge of Re-Injection
Within the **GASC cascade**, water must be re-integrated into the main conduit after passing through the Tesla-Toroid Turbine (TTT). Without precise vector control, the return flow ($v_{ret}$) would decelerate the accelerated core stream ($v_{core}$) through uncontrolled turbulence and momentum loss.

## 2. The Coandă Injection Angle ($\alpha$)
The VIR nozzle utilizes surface adhesion to curved geometries (**Coandă effect**) to "attach" the water as a laminar film to the conduit wall. To maintain boundary layer stability, we define the optimal injection angle $\alpha$:

$$\alpha_{opt} \leq 5^\circ$$

*Condition:* An angle $\alpha > 5^\circ$ leads to flow separation and induces cavitation within the main stream.

## 3. Momentum Conservation and Vector Addition
The resulting velocity $v_{res}$ at the contact point between the core stream and the return flow is calculated via the weighted momentum balance:

$$v_{res} = \frac{\dot{m}_{core} \cdot v_{core} + \dot{m}_{ret} \cdot v_{ret} \cdot \cos(\alpha)}{\dot{m}_{total}}$$

**Parameters:**
- $\dot{m}_{ret}$ : Mass flow rate from the turbine
- Relationship: $\sigma \cdot \dot{m}_{total}$
- $v_{ret}$ : Residual velocity after viscous energy extraction

## 4. The Coandă Pressure Gradient ($\Delta P_c$)
The curvature of the injection lip ($R_{curv}$) creates a local negative pressure gradient that actively sucks the water into the main stream:

$$\Delta P_c = \frac{\rho \cdot v_{ret}^2 \cdot d}{R_{curv}}$$

Where $d$ represents the thickness of the injected water film. This pressure differential stabilizes the laminar flow for the subsequent module $n + 1$.

---

## 🚀 Innovative Advantage (Vector 2030)
Through **VIR technology**, laminar flow within the main conduit is restored artificially faster than in free fall. This enables a drastic increase in **module density** per vertical meter, as the stabilization distance between modules is minimized. 
