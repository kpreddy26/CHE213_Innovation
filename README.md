# CHE213 Innovation Project
# Mass Transfer Dynamics: Solid-Liquid Dissolution

An experimental study evaluating the transport phenomena, boundary layer hydrodynamics, and dissolution kinetics of a benzoic acid–water system under forced convection.

## Project Objectives
* Calculate the liquid-phase mass transfer coefficient ($k_L$) for the benzoic acid–water system.
* Determine the effective stagnant film thickness ($\delta$) utilizing Nernst-Brunner film theory.
* Evaluate convective boundary layer mechanics using dimensionless parameters: Sherwood ($\text{Sh}$), Schmidt ($\text{Sc}$), and Reynolds ($\text{Re}$) numbers.

## Experimental Specifications
* **Pellet Geometry:** Diameter = $32\text{ mm}$, Thickness = $5.65\text{ mm}$, Mass = $5.473\text{ g}$
* **Solvent System:** $1000\text{ mL}$ distilled water agitated via magnetic stirring
* **Analytical Method:** Volumetric titration with $0.02\text{ N}$ Sodium Hydroxide ($\text{NaOH}$) and Phenolphthalein indicator
* **Operation Window:** Aliquot sampling ($10\text{ mL}$) at regular intervals over a $64\text{-minute}$ run till saturation

## Theoretical Framework
The rate of dissolution is modeled using the linearized mass transfer equation:

$$\ln\left(\frac{C_s}{C_s - C_t}\right) = \left(\frac{k_L A}{V}\right)t$$

Where:
* $C_s$ = Saturation concentration
* $C_t$ = Concentration at time $t$
* $A$ = Interfacial surface area ($0.002176\text{ m}^2$)
* $V$ = Effective solvent volume ($830\text{ mL}$ average)

Linear regression modeling performed in the $0\text{--}40\text{ min}$ linear regime ($R^2 = 0.9478$) extracts the empirical slope to isolate $k_L$.

## Key Results
* **Mass Transfer Coefficient ($k_L$):** $1.735 \times 10^{-4}\text{ m/s}$
* **Stagnant Film Thickness ($\delta$):** $6.22\ \mu\text{m}$ (microns)
* **Schmidt Number ($\text{Sc}$):** $768.51$
* **Sherwood Number ($\text{Sh}$):** $5140$
* **Empirical Fit Correlation:** $\text{Sh} = 5.49\,\text{Re}^{0.67}\,\text{Sc}^{1/3}$

## Conclusion
The study validates that forced convective transport strongly dominates over slower molecular diffusion, significantly compressing the boundary layer film thickness ($\delta$) and augmenting system dissolution rates.
