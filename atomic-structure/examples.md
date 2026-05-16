# Atomic Structure — Examples

This file contains selected representative examples from Week 3 questions.

Back to concepts:

⬅️ [Atomic Structure Concepts](./concept.md)

---

## 1. Coulomb Potential Energy of a Bound Electron

**Why this example matters:**  
This example explains why an electron bound to a positive nucleus has negative potential energy. This is the starting point for understanding bound-state energy in atoms.

Related concept: [Coulomb Potential Energy](./concept.md#5-coulomb-potential-energy)

An electron orbits a positive nucleus at radius `r0`.

Electron charge:

```math
q_e=-e
```

Nucleus charge:

```math
q_p=+e
```

Coulomb potential energy is:

```math
PE=\frac{k_e q_1q_2}{r}
```

Substitute:

```math
PE=\frac{k_e(+e)(-e)}{r_0}
```

Therefore:

```math
PE=-\frac{k_e e^2}{r_0}
```

Final result:

```math
\boxed{PE=-\frac{k_e e^2}{r_0}}
```

The negative sign means the electron is bound to the nucleus. Energy must be supplied to remove it.

---

## 2. Bound Electron Energy: PE, KE and Bohr Radius

**Why this example matters:**  
This example connects total energy, potential energy, kinetic energy, and orbital radius. It also fixes a common mistake: kinetic energy is positive, while potential energy is negative.

Related concepts:

- [Bound Electron Energy](./concept.md#6-bound-electron-energy)
- [Bohr Radius](./concept.md#7-bohr-radius)

For the hydrogen ground state:

```math
E_{\text{total}}=-13.6\ \text{eV}
```

The total energy is:

```math
E_{\text{total}}=KE+PE
```

For a Coulomb-bound electron, the kinetic energy is half the magnitude of the potential energy:

```math
KE=\frac{1}{2}|PE|
```

Since the potential energy of an electron bound to a positive nucleus is negative:

```math
PE<0
```

we can also write:

```math
KE=-\frac{1}{2}PE
```

This form is used because it gives a positive kinetic energy.

Substitute:

```math
E_{\text{total}}
=
-\frac{1}{2}PE+PE
=
\frac{1}{2}PE
```

Therefore:

```math
PE=2E_{\text{total}}
```

```math
PE=2(-13.6)=-27.2\ \text{eV}
```

Then:

```math
KE=-\frac{1}{2}PE
```

```math
KE=-\frac{1}{2}(-27.2)=13.6\ \text{eV}
```

Final results:

```math
\boxed{PE=-27.2\ \text{eV}}
```

```math
\boxed{KE=+13.6\ \text{eV}}
```

To estimate the Bohr radius, use:

```math
PE=-\frac{k_e e^2}{r_0}
```

so:

```math
r_0=\frac{k_e e^2}{|PE|}
```

Convert:

```math
27.2\ \text{eV}=27.2\times1.6\times10^{-19}\ \text{J}
```

```math
=4.352\times10^{-18}\ \text{J}
```

Then:

```math
r_0
=
\frac{(8.99\times10^9)(1.6\times10^{-19})^2}
{4.352\times10^{-18}}
```

```math
r_0\approx5.29\times10^{-11}\ \text{m}
```

Final result:

```math
\boxed{r_0\approx5.29\times10^{-11}\ \text{m}}
```

This is the Bohr radius.

---

## 3. Ionisation Energy and Required Photon Wavelength

**Why this example matters:**  
This is the standard method for converting photon energy into wavelength. The same method is later used for LEDs, photodiodes, solar cells, and band-gap questions.

Related concepts:

- [Ionisation Energy](./concept.md#9-ionisation-energy)
- [Photon Absorption and Emission](./concept.md#10-photon-absorption-and-emission)

Ionisation means removing the electron completely:

```math
n=1\rightarrow n=\infty
```

For hydrogen:

```math
E_1=-13.6\ \text{eV}
```

```math
E_\infty=0
```

So the ionisation energy is:

```math
E_{\text{ionisation}}=0-(-13.6)=13.6\ \text{eV}
```

Photon energy is:

```math
E=\frac{hc}{\lambda}
```

Useful form:

```math
\lambda(\text{nm})=\frac{1240}{E(\text{eV})}
```

Therefore:

```math
\lambda=\frac{1240}{13.6}
```

```math
\lambda\approx91.2\ \text{nm}
```

Final result:

```math
\boxed{\lambda\approx91.2\ \text{nm}}
```

This is ultraviolet light. A shorter wavelength would also ionise the atom because shorter wavelength means higher photon energy.

---

## 4. Hydrogen Energy-Level Transition and Emission Wavelength

**Why this example matters:**  
This example combines quantised energy levels with photon emission. It trains you to handle negative energy levels and calculate the emitted photon wavelength.

Related concepts:

- [Energy Levels in Hydrogen](./concept.md#8-energy-levels-in-hydrogen)
- [Photon Absorption and Emission](./concept.md#10-photon-absorption-and-emission)

Before using the energy-level formula, remember the difference between `Z` and `n`:

```math
Z=\text{atomic number}=\text{number of protons}
```

```math
n=\text{principal quantum number}=\text{shell / energy level}
```

For hydrogen:

```math
Z=1
```

The transition `n = 3` to `n = 2` means the electron moves from the third energy level to the second energy level.

Hydrogen energy levels are given by:

```math
E_n=-\frac{13.6Z^2}{n^2}\ \text{eV}
```

For hydrogen:

```math
Z=1
```

so:

```math
E_n=-\frac{13.6}{n^2}\ \text{eV}
```

For `n=2`:

```math
E_2=-\frac{13.6}{2^2}=-3.4\ \text{eV}
```

For `n=3`:

```math
E_3=-\frac{13.6}{3^2}\approx-1.51\ \text{eV}
```

When an electron transitions from `n=3` to `n=2`, it emits a photon.

Photon energy:

```math
E_{\text{photon}}=E_3-E_2
```

```math
E_{\text{photon}}=(-1.51)-(-3.40)
```

```math
E_{\text{photon}}=1.89\ \text{eV}
```

Convert energy to wavelength:

```math
\lambda(\text{nm})=\frac{1240}{E(\text{eV})}
```

```math
\lambda=\frac{1240}{1.89}
```

```math
\lambda\approx656\ \text{nm}
```

Final result:

```math
\boxed{\lambda\approx656\ \text{nm}}
```

This is red visible light.