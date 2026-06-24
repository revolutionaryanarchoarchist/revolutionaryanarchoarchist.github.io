# quantum mchanics

## Failure of Classical Physics

### Blackbody radiation

All bodies emit
 electromagnetic radiation over a range of wavelengths. In an earlier 
chapter, we learned that a cooler body radiates less energy than a 
warmer body. We also know by observation that when a body is heated and 
its temperature rises, the perceived wavelength of its emitted radiation
changes from infrared to red, and then from red to orange, and so 
forth. As its temperature rises, the body glows with the colors 
corresponding to ever-smaller wavelengths of the electromagnetic 
spectrum. This is the underlying principle of the incandescent light 
bulb: A hot metal filament glows red, and when heating continues, its 
glow eventually covers the entire visible portion of the electromagnetic
 spectrum. The temperature (**T**) of the object that emits radiation, or the **emitter**, determines the wavelength at which the radiated energy is at its 
maximum. For example, the Sun, whose surface temperature is in the range
 between 5000 K and 6000 K, radiates most strongly in a range of 
wavelengths about 560 nm in the visible part of the electromagnetic 
spectrum. Your body, when at its normal temperature of about 300 K, 
radiates most strongly in the infrared part of the spectrum. Radiation that 
is incident on an object is partially absorbed and partially reflected. 
At thermodynamic equilibrium, the rate at which an object absorbs 
radiation is the same as the rate at which it emits it. Therefore, a  good absorber of radiation (any object that absorbs radiation) is also a goodemitter. A perfect **absorber** absorbs all electromagnetic radiation incident on it; such an object is called a **blackbody**. 

The intensity $I(\lambda, T)$ of blackbody radiationdepends on the wavelength $\lambda$ of the emitted radiation and on the temperature $T$ of the blackbody. The function $I(\lambda, T)$ is the **power** intensity that is radiated per unit wavelength; in other words, it is the power radiated per unit area of the hole in a cavity radiator per unit wavelength. According to this definition, $I(\lambda, T)d\lambda$ is the power per unit area that is emitted in the wavelength interval from $\lambda$ to $\lambda + d\lambda$. The intensity distribution among wavelengths of radiation emitted by cavities was studied experimentally at the end of the nineteenth century. Generally, radiation emitted by materials only approximately follows the blackbody radiation curve; however, spectra of common stars do follow the blackbody radiation curve very closely. 

Two important laws summarize the experimental findings of

blackbody radiation: ***Wien’s displacement law*** and **Stefan’s law**. Quantitatively, Wien’s law reads:

$\lambda_{max}T=2.898 \times 10^{-3}m . K$

where $\lambda_{max}$ is the position of the maximum in the radiation curve. In other words, $\lambda_{max}$ is the wavelength at which a blackbody radiates most strongly at a given temperature $T$ (in kelvins).

The second experimental relation is **Stefan’s law,** which concerns the total power of blackbody radiation emitted across the entire spectrum of wavelengths at a given temperature. this total power is represented by the area under the blackbody radiation curve for a given **T**. As the temperature of a blackbody increases, the total emitted power also increases. Quantitatively, Stefan’s law expresses this relation as:

$P(T)= \sigma AT^4$ 

where $A$ is the surface area of a blackbody , $T$ is its temperature (in kelvins), and $\sigma$ is the **Stefan–Boltzmann constant**, $\sigma = 5.670 \times 10^-8$ $ \frac{W}{m^2 \cdot K^4}$. Stefan’s law enables us to estimate how much energy a star is radiating by remotely measuring its temperature.

#### Rayleigh–Jeans law

the **Rayleigh–Jeans law** is an approximation to the spectral radiance of electromagnetic radiation as a function of wavelength from a black body at a given temperature through classical arguments. For wavelength λ, it is:

$B_\lambda(T) = \frac{2ck_BT}{\lambda^4}$

where $B_{\lambda }$ is the spectral radiance (the power emitted per unit emitting area, per steradian, per unit wavelength), $c$ is the speed of light, $k_b$ is the Boltzmann constant, and $T$ is the temperature in kelvins. For frequency $v$, the expression is instead:

$B_\lambda(T) = \frac{2v^2k_BT}{c^2}$

##### Ultraviolet catastrophe

Measurements of the spectral emission of actual black bodies revealed that the emission agreed with Rayleigh's calculation at low frequencies but diverged at high frequencies, reaching a maximum and then falling with frequency, so the total energy emitted is finite. Rayleigh recognized the unphysical behavior of his formula at high frequencies and introduced an ad hoc cutoff to correct it, but experimentalists found that his cutoff did not agree with data.Hendrik Lorentz also presented a derivation of the wavelength dependence in 1903. More complete derivations, which included the proportionality constant, were presented in 1905 by Rayleigh and Sir James Jeans and independently by Albert Einstein.Rayleigh believed that this discrepancy could be resolved by the equipartition theorem failing to be valid for high-frequency vibrations, while Jeans argued that the underlying cause was matter and luminiferous aether not being in thermal equilibrium.

#### Wien's law

Wien derived his law from thermodynamic arguments, several years before Planck introduced the quantization of radiation.

Wien's original paper did not contain the Planck constant. In this paper, Wien took the wavelength of black-body radiation and combined it with the Maxwell–Boltzmann energy distribution for atoms. The exponential curve was created by the use of Euler's number e raised to the power of the temperature multiplied by a constant. Fundamental constants were later introduced by Max Planck.

The law may be written as:

$I(v,T) = \frac{2hv^3}{c^2}e^{-\frac{hv}{k_bT}}$

This equation may also be written as:

$I(\lambda,T) = \frac{2hc^2}{\lambda^5}e^{-\frac{hc}{\lambda k_bT}}$

The peak value of this curve, as determined by setting the derivative of the equation equal to zero and solving,[7] occurs at a wavelength:

$\lambda_max = \frac{hc}{5k_bT} \approx 0.2878$ $\frac{cm.k}{T}$,

and frequency:

$v_max = \frac{3k_bT}{h} \approx 6.25 \times 10^{10}$ $\frac{Hz}{K}\cdot T$.

#### Need for quantization

The Wien approximation was originally proposed as a description of the complete spectrum of thermal radiation, although it failed to accurately describe long-wavelength (low-frequency) emission. However, it was soon superseded by Planck's law, which accurately describes the full spectrum, derived by treating the radiation as a photon gas and accordingly applying Bose–Einstein in place of Maxwell–Boltzmann statistics. Planck's law may be given as:

$I(\nu,T) = \frac{2hv^2}{c^2} \frac{1}{e^{\frac{hv}{kT}} - 1}$.

The Wien approximation may be derived from Planck's law by assuming  $h\nu \gg kT$. When this is true, then


