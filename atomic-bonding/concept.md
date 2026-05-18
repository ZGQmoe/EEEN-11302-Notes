# Atoms, Bonding and Crystal Structures

For worked examples, see:

➡️ [Atomic Bonding Examples](./examples.md)

---

## 1. Core Idea

Electronic materials are controlled by electrons.

```math
\text{atomic structure}
\rightarrow
\text{electron configuration}
\rightarrow
\text{valence electrons}
\rightarrow
\text{bonding}
\rightarrow
\text{crystal / band structure}
\rightarrow
\text{electrical behaviour}
```

A bond forms only if the bonded state has lower energy:

```math
E_{\text{bonded}}<E_{\text{separate atoms}}
```

---

## 2. Fundamental Particles

| Particle | Charge | Role |
|---|---:|---|
| Electron | $-1.6\times10^{-19}\ \text{C}$ | controls bonding and electrical behaviour |
| Proton | $+1.6\times10^{-19}\ \text{C}$ | determines atomic number |
| Neutron | $0$ | affects atomic mass |

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

Atomic number:

```math
Z=\text{number of protons}
```

Mass number:

```math
A=Z+N
```

where:

- $Z$: protons
- $N$: neutrons

Neutral atom:

```math
\text{number of electrons}=\text{number of protons}
```

Isotope:

```math
\text{same }Z,\quad \text{different }N
```

Ion:

```math
\text{atom with net charge}
```

| Process | Ion formed |
|---|---|
| loses electrons | positive ion / cation |
| gains electrons | negative ion / anion |

Key reminder:

```math
\text{changing protons changes the element}
```

---

## 4. Bohr Model

In the Bohr model, electrons occupy discrete stationary shells around a positive nucleus.

Principal quantum number:

```math
n=1,2,3,\dots
```

Increasing $n$:

```math
n\uparrow
\Rightarrow
\text{larger shell}
\Rightarrow
\text{higher energy}
```

For hydrogen-like atoms:

```math
E_n=-\frac{13.6Z^2}{n^2}\ \text{eV}
```

where:

- $E_n$: energy of shell $n$
- $Z$: atomic number
- $n$: principal quantum number

For hydrogen:

```math
Z=1
```

Ground state:

```math
n=1,\quad E_1=-13.6\ \text{eV}
```

Ionisation limit:

```math
n=\infty,\quad E_\infty=0
```

Ionisation energy from $n=1$:

```math
E_{\text{ionisation}}=0-(-13.6)=13.6\ \text{eV}
```

---

## 5. Energy Transitions and Photons

Absorption:

```math
\text{lower energy}
\rightarrow
\text{higher energy}
```

Emission:

```math
\text{higher energy}
\rightarrow
\text{lower energy}
```

Photon energy:

```math
E_{\text{photon}}=\Delta E
```

```math
E=hf=\frac{hc}{\lambda}
```

Useful shortcut:

```math
E(\text{eV})=\frac{1240}{\lambda(\text{nm})}
```

So:

```math
\lambda(\text{nm})=\frac{1240}{E(\text{eV})}
```

For emission:

```math
E_{\text{photon}}=E_{\text{initial}}-E_{\text{final}}
```

For absorption:

```math
E_{\text{photon}}=E_{\text{higher}}-E_{\text{lower}}
```

If photon energy exceeds ionisation energy:

```math
K=E_{\text{photon}}-E_{\text{ionisation}}
```

where $K$ is kinetic energy of the emitted electron.

---

## 6. Orbitals and Electron Shells

Bohr model is useful but incomplete.

Quantum view:

```math
\text{electron}
\rightarrow
\text{wavefunction}
\rightarrow
\text{orbital probability cloud}
```

Orbital:

```math
\text{region where electron is likely to be found}
```

Maximum number of electrons in shell $n$:

```math
N=2n^2
```

| Shell $n$ | Maximum electrons |
|---:|---:|
| 1 | 2 |
| 2 | 8 |
| 3 | 18 |
| 4 | 32 |
| 5 | 50 |

---

## 7. Quantum Numbers

An electron state is described by four quantum numbers.

| Symbol | Name | Meaning |
|---|---|---|
| $n$ | principal quantum number | shell / energy level |
| $l$ | orbital quantum number | orbital shape |
| $m$ | magnetic quantum number | orbital orientation |
| $s$ | spin quantum number | electron spin |

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
s=\pm\frac12
```

Orbital labels:

| $l$ | Orbital |
|---:|---|
| 0 | s |
| 1 | p |
| 2 | d |
| 3 | f |

Each orbital holds two electrons with opposite spin.

---

## 8. Valence Electrons

Valence electrons:

```math
\text{outermost electrons}
```

They determine:

- bonding behaviour
- chemical reactivity
- electrical properties

Key link:

```math
\text{electron configuration}
\rightarrow
\text{valence electrons}
\rightarrow
\text{bonding type}
\rightarrow
\text{material behaviour}
```

Atoms with completely filled shells are stable:

```math
\text{filled shell}
\Rightarrow
\text{large energy needed to excite electron}
\Rightarrow
\text{high stability}
```

---

## 9. Coulomb Force and Potential Energy

Coulomb force is electrostatic.

```math
F=\frac{kq_1q_2}{r^2}
```

where:

```math
k=\frac{1}{4\pi\epsilon}
```

For an electron near a positive nucleus:

```math
q_1=+e,\quad q_2=-e
```

So the interaction is attractive.

Coulomb potential energy:

```math
U=\frac{kq_1q_2}{r}
```

For electron-nucleus attraction:

```math
U=-\frac{ke^2}{r}
```

Negative energy means:

```math
U<0
\Rightarrow
\text{electron is bound}
```

---

## 10. Interatomic Force and Bond Formation

When two atoms approach, both attractive and repulsive forces act.

Net force:

```math
F_N=F_A+F_R
```

Attractive force:

```math
F_A\sim-\frac{e^2}{4\pi\epsilon_0r^2}
```

Repulsive force:

```math
F_R\sim\frac{B}{r^m}
```

where:

```math
m>2
```

Repulsion dominates at very small separation because of:

- electron cloud overlap
- electron-electron repulsion
- nucleus-nucleus repulsion
- Pauli exclusion

At equilibrium separation:

```math
F_N=0
```

So:

```math
|F_A|=|F_R|
```

The equilibrium separation is the bond length:

```math
r_0=\text{bond length}
```

---

## 11. Potential Energy Curve

Potential energy reference:

```math
U(\infty)=0
```

At stable bond length:

```math
r=r_0
```

the energy is minimum:

```math
U=U_{\min}
```

Force-energy relation:

```math
F=-\frac{dU}{dr}
```

At equilibrium:

```math
F=0
\Rightarrow
\frac{dU}{dr}=0
```

Important:

```math
r_0\neq \text{where }U=0
```

Instead:

```math
r_0=\text{where }U\text{ is minimum}
```

---

## 12. Bond Energy

Bond energy:

```math
E_0=U(\infty)-U(r_0)
```

Since:

```math
U(\infty)=0
```

then:

```math
E_0=-U(r_0)
```

Meaning:

```math
E_0=\text{energy required to separate bonded atoms}
```

Deeper potential well:

```math
E_0\uparrow
\Rightarrow
\text{stronger bond}
```

Assessment memory:

```math
\text{bond length}=r_0
```

```math
\text{bond energy}=E_0
```

---

## 13. Bonding Types

| Bond type | Electron behaviour | Typical examples | Key property |
|---|---|---|---|
| Ionic | electrons transferred | NaCl, MgO | rigid, brittle, insulating as solid |
| Covalent | electrons shared | diamond, Si, Ge, GaAs | directional, strong |
| Metallic | electrons delocalised | Cu, Al, Fe | conductive, ductile |
| Van der Waals | dipole attraction | Xe, iodine, graphite layers | weak, low melting point |

---

## 14. Ionic Bonding

Ionic bonding usually occurs between a metal and a non-metal.

Basic process:

```math
\text{metal loses electron}
```

```math
\text{non-metal gains electron}
```

This forms:

```math
\text{cation}+\text{anion}
```

Opposite charges attract:

```math
\text{cation}+\text{anion}
\rightarrow
\text{ionic bond}
```

Example:

```math
\text{Na}\rightarrow\text{Na}^+ + e^-
```

```math
\text{Cl}+e^-\rightarrow\text{Cl}^-
```

```math
\text{Na}^+ + \text{Cl}^- \rightarrow \text{NaCl}
```

Ionic solid properties:

- high melting point
- rigid
- brittle
- poor electrical conductivity as solid

Reason:

```math
\text{electrons fixed in ions}
\Rightarrow
\text{no free electrons}
```

---

## 15. Covalent Bonding

Covalent bonding means sharing valence electrons.

```math
\text{shared electrons}
\rightarrow
\text{covalent bond}
```

Shared electron density lies between two positive nuclei.

```math
\text{electron density between nuclei}
\rightarrow
\text{electron-nucleus attraction}
```

Covalent bonds are directional.

Common examples:

- $H_2$
- diamond
- Si
- Ge
- GaAs
- SiC

Typical properties:

- strong bonds
- high melting point
- hard
- low malleability
- poor conductivity if electrons are localised

For silicon:

```math
\text{Si has 4 valence electrons}
```

```math
\text{Si forms 4 covalent bonds}
```

```math
\text{tetrahedral bonding}
\rightarrow
\text{diamond cubic structure}
```

---

## 16. Metallic Bonding

Metallic bonding:

```math
\text{positive metal ions}
+
\text{delocalised electron sea}
\rightarrow
\text{metallic bond}
```

Metals have few valence electrons, which are easy to lose from individual atoms.

```math
\text{valence electrons}
\rightarrow
\text{shared by all ions}
\rightarrow
\text{sea of electrons}
```

Key properties:

- non-directional bonding
- good electrical conductivity
- good thermal conductivity
- ductile
- malleable
- often close-packed structures

Conductivity reason:

```math
\text{delocalised electrons}
\rightarrow
\text{mobile charge carriers}
```

---

## 17. Van der Waals and Hydrogen Bonding

Van der Waals bonding comes from dipole attraction.

Origin:

```math
\text{instantaneous dipole}
\rightarrow
\text{induced dipole}
\rightarrow
\text{weak attraction}
```

Hydrogen bonding:

```math
\text{strong special case of van der Waals-type bonding involving H}
```

Typical properties:

- weak bonding
- low melting point
- soft or easily cleaved
- poor conductivity
- common in molecular / layered solids

Examples:

- solid Xe
- iodine
- dry ice
- graphite layer interaction
- polymers and rubber

---

## 18. Crystal Structure Basics

Crystalline solid:

```math
\text{periodic atomic arrangement}
```

Crystal structure:

```math
\text{lattice}+\text{basis}
```

Key terms:

| Term | Meaning |
|---|---|
| Lattice | periodic array of points |
| Basis | atom/group attached to each lattice point |
| Unit cell | smallest repeating volume |
| Lattice parameter $a$ | unit cell length |

---

## 19. Essential Crystal Structures

### Simple Cubic / SC

```math
\text{corners only}
```

Atoms per cell:

```math
1
```

Coordination number:

```math
6
```

---

### Body-Centred Cubic / BCC

```math
\text{corners + body centre}
```

Atoms per cell:

```math
2
```

Coordination number:

```math
8
```

Examples:

```math
\text{Fe, W, Cr}
```

---

### Face-Centred Cubic / FCC

```math
\text{corners + face centres}
```

Atoms per cell:

```math
4
```

Coordination number:

```math
12
```

Packing factor:

```math
74\%
```

Examples:

```math
\text{Cu, Al, Ni}
```

---

### Hexagonal Close-Packed / HCP

Layer stacking:

```math
ABAB\cdots
```

Conventional atoms per cell:

```math
6
```

Primitive atoms per cell:

```math
2
```

Coordination number:

```math
12
```

Packing factor:

```math
74\%
```

Examples:

```math
\text{Mg, Ti, Zn}
```

---

## 20. Semiconductor and Ionic Crystal Structures

### Diamond Cubic

Common materials:

```math
\text{diamond, Si, Ge}
```

Structure:

```math
\text{FCC lattice}+\text{two identical atom basis}
```

Basis:

```math
(0,0,0)
```

```math
\left(\frac14,\frac14,\frac14\right)
```

Atoms per conventional cell:

```math
8
```

Coordination number:

```math
4
```

Bonding:

```math
\text{tetrahedral covalent}
```

---

### Zincblende

Common materials:

```math
\text{GaAs, InP, ZnS}
```

Structure:

```math
\text{diamond-like, but two different atoms}
```

For GaAs:

```math
\text{As at }(0,0,0)
```

```math
\text{Ga at }\left(\frac14,\frac14,\frac14\right)
```

Coordination number:

```math
4
```

Bonding:

```math
\text{partly ionic-covalent}
```

---

### Rock Salt

Common materials:

```math
\text{NaCl, MgO}
```

Structure:

```math
\text{FCC lattice}+\text{two-ion basis}
```

Arrangement:

```math
\text{alternating cations and anions}
```

Coordination number:

```math
6
```

Bonding:

```math
\text{ionic}
```

---

## 21. Bonding, Structure and Electrical Behaviour

### Metals

```math
\text{metallic bonding}
\rightarrow
\text{delocalised electrons}
\rightarrow
\text{partially filled / overlapping bands}
\rightarrow
\text{conductor}
```

### Semiconductors

```math
\text{covalent bonding}
\rightarrow
\text{diamond cubic or zincblende}
\rightarrow
\text{moderate band gap}
\rightarrow
\text{controllable conductivity}
```

Example:

```math
E_g(\text{Si})\approx1.1\ \text{eV}
```

### Insulators

```math
\text{ionic or strong covalent bonding}
\rightarrow
\text{localised electrons}
\rightarrow
\text{large band gap}
\rightarrow
\text{insulator}
```

---

## 22. Key Formula Chain

Atomic mass:

```math
A=Z+N
```

Hydrogen-like energy levels:

```math
E_n=-\frac{13.6Z^2}{n^2}\ \text{eV}
```

Photon energy:

```math
E=hf=\frac{hc}{\lambda}
```

Shortcut:

```math
E(\text{eV})=\frac{1240}{\lambda(\text{nm})}
```

Maximum electrons in shell:

```math
N=2n^2
```

Coulomb force:

```math
F=\frac{kq_1q_2}{r^2}
```

Coulomb potential energy:

```math
U=\frac{kq_1q_2}{r}
```

Attractive electron-nucleus energy:

```math
U_A\sim-\frac{e^2}{4\pi\epsilon_0r}
```

Repulsive energy:

```math
U_R\sim\frac{B}{r^{m+1}}
```

Force-energy relation:

```math
F=-\frac{dU}{dr}
```

Equilibrium bond condition:

```math
F_N=0
```

Bond energy:

```math
E_0=U(\infty)-U(r_0)
```

Since:

```math
U(\infty)=0
```

then:

```math
E_0=-U(r_0)
```

Crystal structure:

```math
\text{crystal structure}=\text{lattice}+\text{basis}
```