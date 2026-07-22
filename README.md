# general-conditions-ADCP
Notebooks for the calculations in https://arxiv.org/abs/2604.18687

conductivity-saddle-point.nb.  - For figure 3c and 3d.  Longitudinal conductivities in $x$ and $y$ direction as a function of Fermi energy.   Note that the conductivity plotted here is expressed in units of $e^2 \mathcal{E}_0 \tau / \hbar^2$ rather than the conventional unit $e^2/\hbar$. Since the momentum relaxation time $\tau$ in a metal is typically much larger than $\hbar/\mathcal{E}_0$, the apparently small conductivity values in the plots actually correspond to very large conductivities in units of $e^2/\hbar$, as expected.

Complianceconstantcals.nb - Calculates compliance constants for the materials. Used in uniaxial-GaAs-ADCP-calc.nb, which is used for Table II and Table III. 


uniaxial-GaAs-ADCP-calc.nb - Checks if ADCP is exhibited for several values of stress and relaxation time ratio ($\tau_h/\tau_e$) for GaAs, same notebook can be used to check for other materials with the relevant values entered.

