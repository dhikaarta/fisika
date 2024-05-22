# Calculation of Aqueous PS Particle Dispersion

**Problem 14:** A monodisperse suspension of latex particles can be produced in water through a radical polymerization of styrene monomers. The generated particles are typically called polystyrene latex (PS) particles or latex particles, for short. The particles are spherical, with a uniform diameter. These dispersions are often used as a type of standard to calibrate scientific instruments. Calculate the following quantities of the aqueous PS particle dispersion.

1. Terminal settling velocity of PS particles with a diameter of 1.0 micrometers in water under gravity. Assume the specific gravity of PS particles to be 1.05.
2. Decay distance of the particle concentration profile in water in the vertical direction (away from gravity). Assume a Boltzmann distribution is formed. The decay distance means the distance over which the value of the number concentration of PS particles decreases by a factor of 1/e.
3. How will these values change if the diameter of the PS particle decreases to 0.1 micrometers.

**Given data:**
- Diameter of PS particle, d = 1.0 micrometers = 1.0 × 10^(-6) m
- Radius of PS particle, r = d/2 = 0.5 × 10^(-6) m
- Density of PS particle, ρ_p = 1.05 × 10^3 kg/m^3
- Density of water, ρ_f = 1.0 × 10^3 kg/m^3
- Dynamic viscosity of water at room temperature, η ≈ 1.0 × 10^(-3) Pa·s
- Acceleration due to gravity, g = 9.81 m/s^2

## (1) Terminal Settling Velocity

Using Stokes' law for small Reynolds numbers (laminar flow):
\[ v_t = \frac{2 (ρ_p - ρ_f) g r^2}{9 η} \]

For diameter d = 1.0 micrometers:
\[ v_t = \frac{2 (1.05 × 10^3 - 1.0 × 10^3) × 9.81 × (0.5 × 10^(-6))^2}{9 × 1.0 × 10^(-3)} \]
\[ v_t ≈ 1.09 × 10^(-7) m/s \]

Therefore, the terminal settling velocity is approximately 1.09 × 10^(-7) m/s.

## (2) Decay Distance

Using the Boltzmann distribution:
\[ h = \frac{k_B T}{mg} \]

Mass of a single particle:
\[ m = \frac{4}{3} π r^3 ρ_p \]
\[ m ≈ 5.5 × 10^(-19) kg \]

Assuming the temperature T is 298 K (25°C):
\[ h = \frac{1.38 × 10^(-23) × 298}{5.5 × 10^(-19) × 9.81} \]
\[ h ≈ 0.763 mm \]

Therefore, the decay distance is approximately 0.763 mm.

## (3) Values for 0.1 Micrometers Diameter

### Terminal Settling Velocity

For diameter d = 0.1 micrometers:
\[ v_t = \frac{2 (1.05 × 10^3 - 1.0 × 10^3) × 9.81 × (0.05 × 10^(-6))^2}{9 × 1.0 × 10^(-3)} \]
\[ v_t ≈ 2.72 × 10^(-10) m/s \]

Therefore, the terminal settling velocity is approximately 2.72 × 10^(-10) m/s.

### Decay Distance

For the new particle mass:
\[ m ≈ 5.5 × 10^(-22) kg \]

Using the decay distance formula:
\[ h = \frac{1.38 × 10^(-23) × 298}{5.5 × 10^(-22) × 9.81} \]
\[ h ≈ 0.76 m \]

Therefore, the decay distance is approximately 0.76 m.

## Summary

1. **Terminal Settling Velocity:**
   - For 1.0 micrometers diameter: 1.09 × 10^(-7) m/s
   - For 0.1 micrometers diameter: 2.72 × 10^(-10) m/s

2. **Decay Distance:**
   - For 1.0 micrometers diameter: 0.763 mm
   - For 0.1 micrometers diameter: 0.76 m

