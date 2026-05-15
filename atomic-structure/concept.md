# Atomic Structure

This file contains core concepts, rules, and formulas for atomic structure.

For selected worked examples based on Week 3 questions, see:

➡️ [Atomic Structure Examples](./examples.md)

---

## 1. Why Atomic Structure Matters

Atomic structure explains why different materials behave as conductors, semiconductors, or insulators.

The key chain is:

```math
\text{Atomic structure}
\rightarrow
\text{Electron configuration}
\rightarrow
\text{Bonding}
\rightarrow
\text{Band structure}
\rightarrow
\text{Electrical behaviour}
```

In electronic materials, the most important particle is the electron because electron movement determines electrical conductivity.

---

## 2. Fundamental Particles

Atoms are made from electrons, protons and neutrons.

| Particle | Charge | Relative charge | Role |
|---|---:|---:|---|
| Electron | `-1.6 × 10^-19 C` | `-1` | controls electrical behaviour |
| Proton | `+1.6 × 10^-19 C` | `+1` | determines atomic number |
| Neutron | `0` | `0` | affects atomic mass |

Electron charge magnitude:

```math
e=1.6\times10^{-19}\ \text{C}
```

Electron charge:

```math
q_e=-e
```

Proton charge:

```math
q_p=+e
```

---

## 3. Atomic Number, Mass Number, Isotopes and Ions

### 3.1 Atomic Number

The atomic number is the number of protons.

```math
Z=\text{number of protons}
```

The atomic number determines the element.

---

### 3.2 Mass Number

The mass number is the total number of protons and neutrons.

```math
A=Z+N
```

where:

- `Z` = number of protons
- `N` = number of neutrons

---

### 3.3 Neutral Atom

For a neutral atom:

```math
\text{number of electrons}=\text{number of protons}
```

---

### 3.4 Isotope

Isotopes have the same number of protons but different numbers of neutrons.

```math
\text{same }Z,\quad \text{different }N
```

---

### 3.5 Ion

An ion is an atom with net charge due to losing or gaining electrons.

If an atom loses electrons:

```math
\text{positive ion / cation}
```

If an atom gains electrons:

```math
\text{negative ion / anion}
```

---

## 4. Planetary / Bohr Model of the Atom

In the planetary model, an electron orbits a positive nucleus.

For hydrogen:

```math
\text{nucleus charge}=+e
```

```math
\text{electron charge}=-e
```

The electron is attracted to the nucleus by electrostatic force.

This model is simplified, but it is useful for calculating:

- electron potential energy
- total energy
- orbit radius
- ionisation energy
- photon wavelength

📘 Example: [Coulomb potential energy of a bound electron](./examples.md#1-coulomb-potential-energy-of-a-bound-electron)

---

## 5. Coulomb Potential Energy

The electrostatic potential energy between two point charges is:

```math
PE=\frac{k_e q_1q_2}{r}
```

where:

- `PE` = electrostatic potential energy
- `k_e` = Coulomb constant
- `q_1`, `q_2` = charges
- `r` = separation between charges

Coulomb constant:

```math
k_e=8.99\times10^9\ \text{N m}^2\text{C}^{-2}
```

For an electron orbiting a positive nucleus:

```math
q_1=+e
```

```math
q_2=-e
```

Therefore:

```math
PE=\frac{k_e(+e)(-e)}{r_0}
```

So:

```math
PE=-\frac{k_e e^2}{r_0}
```

The negative sign means the electron is bound to the nucleus.

📘 Example: [Coulomb potential energy of a bound electron](./examples.md#1-coulomb-potential-energy-of-a-bound-electron)

---

## 6. Bound Electron Energy

The total energy of a bound electron is:

```math
E_{\text{total}}=KE+PE
```

For a Coulomb-bound electron:

```math
KE=-\frac{1}{2}PE
```

This means:

- potential energy is negative
- kinetic energy is positive
- total energy is negative

For the hydrogen ground state:

```math
E_{\text{total}}=-13.6\ \text{eV}
```

Then:

```math
PE=-27.2\ \text{eV}
```

```math
KE=+13.6\ \text{eV}
```

📘 Example: [Bound electron energy: PE, KE and Bohr radius](./examples.md#2-bound-electron-energy-pe-ke-and-bohr-radius)

---

## 7. Bohr Radius

The radius of the hydrogen ground-state orbit can be found from:

```math
PE=-\frac{k_e e^2}{r_0}
```

Rearrange:

```math
r_0=\frac{k_e e^2}{|PE|}
```

For the hydrogen ground state:

```math
|PE|=27.2\ \text{eV}
```

Convert electron-volts to joules:

```math
1\ \text{eV}=1.6\times10^{-19}\ \text{J}
```

The result is:

```math
r_0\approx5.29\times10^{-11}\ \text{m}
```

This is the Bohr radius.

```math
r_0\approx0.529\ \text{\AA}
```

📘 Example: [Bound electron energy: PE, KE and Bohr radius](./examples.md#2-bound-electron-energy-pe-ke-and-bohr-radius)

---

## 8. Energy Levels in Hydrogen

Electron energy levels in hydrogen are quantised.

For hydrogen-like atoms:

```math
E_n=-\frac{13.6Z^2}{n^2}\ \text{eV}
```

where:

- `E_n` = energy level
- `Z` = atomic number
- `n` = principal quantum number

For hydrogen:

```math
Z=1
```

so:

```math
E_n=-\frac{13.6}{n^2}\ \text{eV}
```

Important hydrogen levels:

```math
E_1=-13.6\ \text{eV}
```

```math
E_2=-3.4\ \text{eV}
```

```math
E_3=-1.51\ \text{eV}
```

As `n` increases, the energy becomes less negative and approaches zero.

```math
E_{\infty}=0
```

📘 Example: [Hydrogen energy-level transition and emission wavelength](./examples.md#4-hydrogen-energy-level-transition-and-emission-wavelength)

---

## 9. Ionisation Energy

Ionisation means removing an electron completely from the atom.

For the hydrogen ground state:

```math
n=1\rightarrow n=\infty
```

Energy at infinity:

```math
E_{\infty}=0
```

Ground state energy:

```math
E_1=-13.6\ \text{eV}
```

So the ionisation energy is:

```math
E_{\text{ionisation}}=0-(-13.6)=13.6\ \text{eV}
```

📘 Example: [Ionisation energy and required photon wavelength](./examples.md#3-ionisation-energy-and-required-photon-wavelength)

---

## 10. Photon Absorption and Emission

A photon has energy:

```math
E=hf
```

Since:

```math
f=\frac{c}{\lambda}
```

we get:

```math
E=\frac{hc}{\lambda}
```

Therefore:

```math
\lambda=\frac{hc}{E}
```

Useful shortcut:

```math
E(\text{eV})=\frac{1240}{\lambda(\text{nm})}
```

or:

```math
\lambda(\text{nm})=\frac{1240}{E(\text{eV})}
```

---

### 10.1 Absorption

If an electron moves from a lower energy level to a higher energy level, it absorbs energy.

```math
\text{lower energy level}
\rightarrow
\text{higher energy level}
```

---

### 10.2 Emission

If an electron moves from a higher energy level to a lower energy level, it emits a photon.

```math
\text{higher energy level}
\rightarrow
\text{lower energy level}
```

Photon energy:

```math
E_{\text{photon}}=E_{\text{initial}}-E_{\text{final}}
```

📘 Examples:

- [Ionisation energy and required photon wavelength](./examples.md#3-ionisation-energy-and-required-photon-wavelength)
- [Hydrogen energy-level transition and emission wavelength](./examples.md#4-hydrogen-energy-level-transition-and-emission-wavelength)

---

## 11. Quantum View of Electrons

The Bohr model is useful but incomplete.

In the quantum model, electrons are not particles moving in fixed circular paths.

Instead, electrons are described by wavefunctions and orbitals.

An orbital gives the probability of finding an electron in a region of space.

---

## 12. De Broglie Wavelength

A moving particle has an associated wavelength:

```math
\lambda=\frac{h}{mv}
```

where:

- `h` = Planck constant
- `m` = particle mass
- `v` = particle velocity

For electrons in atoms, this wavelength is comparable to atomic dimensions, so quantum behaviour is important.

---

## 13. Schrödinger Equation

The quantum behaviour of electrons is described by:

```math
\hat{H}|\psi\rangle=E|\psi\rangle
```

where:

- `\hat{H}` = Hamiltonian operator
- `|\psi\rangle` = wavefunction
- `E` = allowed energy level

The wavefunction describes electron probability distribution.

---

## 14. Quantum Numbers

An electron state is described by four quantum numbers.

| Symbol | Name | Meaning |
|---|---|---|
| `n` | principal quantum number | shell / main energy level |
| `l` | orbital quantum number | orbital shape |
| `m` | magnetic quantum number | orbital orientation |
| `s` | spin quantum number | electron spin |

Allowed values:

```math
n=1,2,3,\dots
```

```math
l=0,1,\dots,n-1
```

```math
m=-l,\dots,0,\dots,+l
```

```math
s=\pm\frac{1}{2}
```

Orbital labels:

| `l` | Orbital type |
|---:|---|
| 0 | s |
| 1 | p |
| 2 | d |
| 3 | f |

---

## 15. Maximum Electrons Per Shell

Each orbital can hold two electrons with opposite spin.

The maximum number of electrons in shell `n` is:

```math
N=2n^2
```

Examples:

| Shell `n` | Maximum electrons |
|---:|---:|
| 1 | 2 |
| 2 | 8 |
| 3 | 18 |
| 4 | 32 |

---

## 16. Valence Electrons

Electrons fill the lowest available energy levels first.

The outermost electrons are called valence electrons.

Valence electrons determine:

- bonding behaviour
- chemical reactivity
- electrical properties

Key link:

```math
\text{electron configuration}
\rightarrow
\text{valence electrons}
\rightarrow
\text{bonding}
\rightarrow
\text{material behaviour}
```