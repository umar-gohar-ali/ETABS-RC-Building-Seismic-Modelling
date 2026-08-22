# Target Displacement Calculation (FEMA-356)

δt = C0 * C1 * C2 * C3 * Sa * (Te^2 / 4π²) * g

Where:
- C0 = modification factor, roof displacement vs spectral displacement
- C1 = modification factor, inelastic vs elastic displacement
- C2 = modification factor, hysteresis shape effect
- C3 = modification factor, P-delta/negative stiffness effect
- Sa = spectral acceleration at effective period
- Te = effective fundamental period
- g  = gravitational acceleration

DBE target displacement computed directly from equation.
SLE = DBE spectral value / 1.4
MCE = DBE spectral value x 1.5