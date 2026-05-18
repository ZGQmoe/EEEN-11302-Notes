# Band Theory

For examples, see:

➡️ [Band Theory Examples](./examples.md)

---

## 1. Core Idea

Band theory explains how isolated atomic energy levels become energy bands in solids.

```math
\text{isolated atoms}
\rightarrow
\text{orbital overlap}
\rightarrow
\text{level splitting}
\rightarrow
\text{energy bands}
\rightarrow
\text{electrical behaviour}
```

In solids, many atoms are close together, so atomic orbitals overlap.

```math
N\ \text{atoms}
\rightarrow
N\ \text{orbitals}
\rightarrow
N\ \text{energy levels}
```

Including spin:

```math
N\ \text{orbitals}
\rightarrow
2N\ \text{states}
```

---

## 2. Wavefunction and Orbital

Wavefunction:

```math
\psi=\text{wavefunction}
```

Electron probability density:

```math
|\psi|^2=\text{electron probability density}
```

Atomic orbital:

```math
\text{allowed electron state around one atom}
```

Examples:

```math
1s,\ 2s,\ 2p,\ 3s,\dots
```

Key idea:

```math
\text{orbital is described by a wavefunction}
```

---

## 3. Bonding and Anti-Bonding Orbitals

When two atomic wavefunctions overlap, they combine.

Bonding orbital:

```math
\psi_{\text{bonding}}=\psi_A+\psi_B
```

Anti-bonding orbital:

```math
\psi_{\text{anti-bonding}}=\psi_A-\psi_B
```

---

### 3.1 Bonding Orbital

```math
\text{in phase}
\rightarrow
\text{constructive interference}
\rightarrow
\text{more electron density between nuclei}
```

Energy:

```math
E_{\text{bonding}}<E_{\text{atomic}}
```

Reason:

```math
\text{more electron density between nuclei}
\Rightarrow
\text{stronger attraction}
\Rightarrow
\text{lower energy}
```

---

### 3.2 Anti-Bonding Orbital

```math
\text{out of phase}
\rightarrow
\text{destructive interference}
\rightarrow
\text{node between nuclei}
```

At the node:

```math
\psi=0
```

```math
|\psi|^2=0
```

Energy:

```math
E_{\text{anti-bonding}}>E_{\text{atomic}}
```

Reason:

```math
\text{less electron density between nuclei}
\Rightarrow
\text{higher energy}
```

---

## 4. Energy Level Splitting

For two atoms:

```math
2\ \text{atomic orbitals}
\rightarrow
2\ \text{molecular orbitals}
```

Energy order:

```math
E_{\text{bonding}}<E_{\text{atomic}}<E_{\text{anti-bonding}}
```

For $N$ atoms:

```math
N\ \text{atomic orbitals}
\rightarrow
N\ \text{closely spaced levels}
```

For a solid:

```math
N\sim10^{23}
```

Therefore:

```math
\text{many closely spaced levels}
\rightarrow
\text{energy band}
```

---

## 5. Energy Band Formation in Metals

In metals, atomic orbitals overlap strongly.

```math
\text{overlapping atomic orbitals}
\rightarrow
\text{overlapping bands}
\rightarrow
\text{nearly continuous energy band}
```

For an isolated metal atom, levels may be labelled:

```math
E_{1s},\ E_{2s},\ E_{2p},\ E_{3s}
```

In a solid:

```math
\text{atomic levels broaden into bands}
```

In metals:

```math
\text{bands overlap}
```

or:

```math
\text{a band is partially filled}
```

Therefore:

```math
\text{nearby empty states exist}
\Rightarrow
\text{electrons can move}
\Rightarrow
\text{metal conducts}
```

---

## 6. Full, Empty and Partially Filled Bands

Electrons fill lower energy states first.

Full band:

```math
\text{all states occupied}
```

```math
\text{no nearby empty states}
\Rightarrow
\text{poor conduction}
```

Empty band:

```math
\text{no electrons}
\Rightarrow
\text{no current contribution}
```

Partially filled band:

```math
\text{electrons + nearby empty states}
\Rightarrow
\text{good conduction}
```

Key rule:

```math
\text{partially filled band}
\Rightarrow
\text{metallic conduction}
```

---

## 7. Lithium Example

Lithium electron configuration:

```math
1s^2 2s^1
```

For $N$ Li atoms:

```math
1s^2
\Rightarrow
2N\ \text{electrons}
```

The $1s$ band has:

```math
2N\ \text{states}
```

Therefore:

```math
1s\ \text{band full}
```

For the $2s$ band:

```math
2s^1
\Rightarrow
N\ \text{electrons}
```

The $2s$ band has:

```math
2N\ \text{states}
```

Therefore:

```math
2s\ \text{band half-filled}
```

So:

```math
\text{half-filled band}
\Rightarrow
\text{metallic conduction}
```

---

## 8. Vacuum Level

Vacuum level:

```math
E_{\text{vac}}
```

Meaning:

```math
E_{\text{vac}}=\text{energy of an electron just free from the solid}
```

If:

```math
E<E_{\text{vac}}
```

then:

```math
\text{electron is bound inside the material}
```

If:

```math
E=E_{\text{vac}}
```

then:

```math
\text{electron is just outside / free from the solid}
```

Short memory:

```math
E_{\text{vac}}=\text{escape energy level}
```

---

## 9. Fermi Level

Fermi level:

```math
E_F=\text{energy level with 50% occupation probability}
```

At $T=0\,\text{K}$:

```math
E<E_F
\Rightarrow
\text{states filled}
```

```math
E>E_F
\Rightarrow
\text{states empty}
```

So at $0\,\text{K}$:

```math
E_F=\text{highest occupied energy level}
```

For metals:

```math
E_F\text{ lies inside a band}
```

This means:

```math
\text{filled states below }E_F
+
\text{empty states above }E_F
```

Therefore:

```math
\text{electrons near }E_F
\Rightarrow
\text{main conduction electrons}
```

---

## 10. Fermi Energy

Fermi energy can depend on the chosen reference.

Measured from band bottom:

```math
E_F-E_b
```

Measured from vacuum level:

```math
E_{\text{vac}}-E_F
```

Key distinction:

```math
\text{Fermi level}=\text{energy position}
```

```math
\text{Fermi energy}=\text{energy difference from a reference}
```

At $0\,\text{K}$, in a free-electron metal:

```math
E_F=\text{maximum occupied kinetic energy}
```

Reason:

```math
\text{Pauli exclusion principle}
```

So:

```math
0\,\text{K}
\neq
\text{all electrons have zero energy}
```

Instead:

```math
0\,\text{K}
=
\text{all states filled up to }E_F
```

---

## 11. Fermi-Dirac Distribution

Fermi-Dirac distribution:

```math
f(E)=\text{probability that a state at energy }E\text{ is occupied}
```

Formula:

```math
f(E)=\frac{1}{1+e^{(E-E_F)/(k_BT)}}
```

At $E=E_F$:

```math
f(E_F)=\frac{1}{2}
```

At $T=0\,\text{K}$:

```math
E<E_F\Rightarrow f(E)=1
```

```math
E>E_F\Rightarrow f(E)=0
```

So:

```math
f(E)=\text{sharp step at }E_F
```

At $T>0\,\text{K}$:

```math
\text{sharp step}
\rightarrow
\text{broadened step}
```

Higher temperature:

```math
T\uparrow
\Rightarrow
\text{broader transition around }E_F
```

---

## 12. Density of States and Electron Distribution

Density of states:

```math
g(E)=\text{available states per unit energy per unit volume}
```

For free electrons:

```math
g(E)\propto E^{1/2}
```

Electron concentration per unit energy:

```math
n_E=g(E)f(E)
```

Meaning:

```math
\text{actual electrons at energy }E
=
\text{available states}
\times
\text{occupation probability}
```

Electrons in energy range $E$ to $E+dE$:

```math
n_EdE
```

Total electron concentration:

```math
n=\int n_E\,dE
```

or:

```math
n=\int g(E)f(E)\,dE
```

Average electron energy:

```math
E_{\text{average}}
=
\frac{\int E n_E\,dE}{n}
```

For a free-electron metal at $0\,\text{K}$:

```math
E_{\text{average}}\approx\frac{3}{5}E_F
```

---

## 13. Work Function in Metals

Work function:

```math
\Phi=E_{\text{vac}}-E_F
```

Meaning:

```math
\Phi=\text{minimum energy needed to release an electron from a metal}
```

More specifically:

```math
\Phi=\text{energy needed to move an electron from }E_F\text{ to }E_{\text{vac}}
```

Larger work function:

```math
\Phi\uparrow
\Rightarrow
\text{electron harder to remove}
```

Smaller work function:

```math
\Phi\downarrow
\Rightarrow
\text{electron easier to remove}
```

Key reminder:

```math
\text{electron removal starts from }E_F
```

not from the band bottom.

---

## 14. Metal Energy Band Diagram

For a metal:

```math
E_b=\text{bottom of energy band}
```

```math
E_F=\text{Fermi level}
```

```math
E_{\text{vac}}=\text{vacuum level}
```

```math
\Phi=\text{work function}
```

Relations:

```math
\Phi=E_{\text{vac}}-E_F
```

```math
E_{\text{vac}}=E_F+\Phi
```

If the band bottom is chosen as reference:

```math
E_b=0
```

then:

```math
E_F-E_b=\text{Fermi energy measured from band bottom}
```

Metal conduction:

```math
\text{partially filled band crossing }E_F
\Rightarrow
\text{conduction}
```

---

## 15. Metal-Metal Contact and Contact Potential

Different metals can have different work functions.

Since:

```math
\Phi=E_{\text{vac}}-E_F
```

smaller work function means:

```math
\Phi\downarrow
\Rightarrow
E_F\uparrow
\quad\text{relative to vacuum}
```

When two metals contact:

```math
\text{electrons move from higher }E_F\text{ to lower }E_F
```

Electron transfer continues until:

```math
E_F\text{ levels align}
```

At equilibrium:

```math
\text{Fermi level is flat / aligned}
```

Charge separation creates:

```math
\text{contact potential}
```

Contact potential energy:

```math
e\Delta V=\Delta\Phi
```

or:

```math
e\Delta V=\Phi_2-\Phi_1
```

If using eV units:

```math
\Delta V\text{ in volts}
=
\text{work function difference in eV}
```

---

## 16. Energy-Momentum Diagrams

Energy-momentum diagram plots:

```math
E\text{ vs }k
```

Crystal momentum:

```math
p=\hbar k
```

Free-electron kinetic energy:

```math
E=\frac{p^2}{2m}
```

Using effective mass:

```math
E=\frac{p^2}{2m^*}
```

Therefore:

```math
E\text{-}k\text{ curve is parabolic}
```

---

## 17. Effective Mass

Effective mass describes how easily an electron or hole responds to force inside a crystal.

```math
m^*=\text{carrier inertia inside a crystal}
```

From band curvature:

```math
m^*=\frac{\hbar^2}{d^2E/dk^2}
```

Smaller effective mass:

```math
m^*\downarrow
\Rightarrow
\text{carrier accelerates more easily}
```

Mobility trend:

```math
\mu\propto\frac{1}{m^*}
```

Effective mass is often written as:

```math
m^*=\alpha m_e
```

where:

- $m_e$: free electron mass
- $\alpha$: dimensionless constant

---

## 18. Origin of Holes in Semiconductors

In a nearly full valence band, an empty state behaves like a positive carrier.

Hole:

```math
\text{missing electron in the valence band}
```

Hole effective mass:

```math
m_h^*
```

It is also determined by band curvature:

```math
m_h^*=\frac{\hbar^2}{d^2E/dk^2}
```

Key idea:

```math
\text{hole}
=
\text{empty state behaving like positive mobile charge}
```

Holes are mainly used when interpreting semiconductor conduction.

---

## 19. Band Gaps

Band gap:

```math
E_g=E_C-E_V
```

where:

- $E_C$: bottom of conduction band
- $E_V$: top of valence band

Meaning:

```math
E_g=\text{energy needed to excite electron from valence band to conduction band}
```

Large band gap:

```math
E_g\uparrow
\Rightarrow
\text{fewer charge carriers}
\Rightarrow
\text{lower conductivity}
```

Small band gap:

```math
E_g\downarrow
\Rightarrow
\text{more charge carriers at room temperature}
\Rightarrow
\text{higher conductivity}
```

---

## 20. Semiconductor and Insulator Band Diagrams

Basic diagram:

```text
Energy ↑

E_vac  ─────────────────────  Vacuum level
       ↑
       │ χ = electron affinity
       ↓
E_C    ─────────────────────  Bottom of conduction band
       ↑
       │ E_g = band gap
       ↓
E_V    ─────────────────────  Top of valence band
```

Band edges:

```math
E_C=\text{bottom of conduction band}
```

```math
E_V=\text{top of valence band}
```

At $T=0\,\text{K}$:

```math
\text{valence band full}
```

```math
\text{conduction band empty}
```

At $T>0\,\text{K}$, in a semiconductor:

```math
\text{some electrons thermally excited to conduction band}
```

---

## 21. Electron Affinity

Electron affinity:

```math
\chi=E_{\text{vac}}-E_C
```

Meaning:

```math
\chi=\text{energy from conduction band edge to vacuum level}
```

or:

```math
\chi=\text{energy needed to remove electron from }E_C\text{ to vacuum}
```

Larger electron affinity:

```math
\chi\uparrow
\Rightarrow
E_C\text{ deeper below vacuum}
```

---

## 22. Work Function vs Electron Affinity vs Band Gap

Work function:

```math
\Phi=E_{\text{vac}}-E_F
```

Electron affinity:

```math
\chi=E_{\text{vac}}-E_C
```

Band gap:

```math
E_g=E_C-E_V
```

| Quantity | Formula | Measures |
|---|---|---|
| Work function | $\Phi=E_{\text{vac}}-E_F$ | vacuum level to Fermi level |
| Electron affinity | $\chi=E_{\text{vac}}-E_C$ | vacuum level to conduction band edge |
| Band gap | $E_g=E_C-E_V$ | conduction band edge to valence band edge |

Key reminder:

```math
\Phi\text{ uses }E_F
```

```math
\chi\text{ uses }E_C
```

```math
E_g\text{ uses }E_C\text{ and }E_V
```

---

## 23. Metals vs Semiconductors vs Insulators

| Property | Metal | Semiconductor | Insulator |
|---|---|---|---|
| Energy gap | none | small | large |
| Band overlap | yes | no | no |
| Valence band | full / overlapping | full | full |
| Conduction band | filled up to $E_F$ | empty at $0K$, partly filled at $T>0K$ | empty |
| Conductivity | very high | moderate / controllable | negligible |
| Current flow | free electrons | electrons and holes | negligible |

---

## 24. Conductivity from Band Theory

### Metal

```math
\text{partially filled band or overlapping bands}
\Rightarrow
\text{many mobile electrons}
\Rightarrow
\text{high conductivity}
```

### Semiconductor

```math
\text{small band gap}
\Rightarrow
\text{some thermally excited electrons and holes}
\Rightarrow
\text{moderate conductivity}
```

### Insulator

```math
\text{large band gap}
\Rightarrow
\text{almost no carriers}
\Rightarrow
\text{negligible conductivity}
```

---

## 25. Key Formula Chain

Bonding / anti-bonding:

```math
\psi_{\text{bonding}}=\psi_A+\psi_B
```

```math
\psi_{\text{anti-bonding}}=\psi_A-\psi_B
```

Band formation:

```math
N\ \text{orbitals}
\rightarrow
N\ \text{levels}
\rightarrow
2N\ \text{states with spin}
```

Band gap:

```math
E_g=E_C-E_V
```

Vacuum level relation:

```math
\Phi=E_{\text{vac}}-E_F
```

```math
\chi=E_{\text{vac}}-E_C
```

Work function:

```math
\Phi=E_{\text{vac}}-E_F
```

Contact potential:

```math
e\Delta V=\Delta\Phi
```

Crystal momentum:

```math
p=\hbar k
```

Free-electron energy:

```math
E=\frac{p^2}{2m^*}
```

Effective mass:

```math
m^*=\frac{\hbar^2}{d^2E/dk^2}
```

Fermi-Dirac distribution:

```math
f(E)=\frac{1}{1+e^{(E-E_F)/(k_BT)}}
```

Electron distribution:

```math
n_E=g(E)f(E)
```

Total electron concentration:

```math
n=\int g(E)f(E)\,dE
```