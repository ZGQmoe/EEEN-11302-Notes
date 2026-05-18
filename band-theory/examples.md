# Band Theory Examples

Related concept notes:

➡️ [Band Theory](./concept.md)

---

## Example 1: Wavefunction vs Orbital

Question:

What is the difference between a wavefunction and an atomic orbital?

Answer:

```math
\psi=\text{wavefunction}
```

```math
|\psi|^2=\text{electron probability density}
```

An atomic orbital is:

```math
\text{an allowed electron state around an atom}
```

The orbital is described by a wavefunction.

```math
\text{wavefunction}
\rightarrow
\text{mathematical description}
```

```math
\text{orbital}
\rightarrow
\text{physical electron state / probability cloud}
```

Short answer:

```math
\boxed{\text{They are closely related, but not exactly the same.}}
```

---

## Example 2: Isolated Hydrogen Atoms

For two isolated hydrogen atoms:

```math
R=\infty
```

Each atom has its own $1s$ wavefunction:

```math
\psi_{1s}(r_A)
```

```math
\psi_{1s}(r_B)
```

Since the atoms are far apart:

```math
\text{no wavefunction overlap}
```

Therefore:

```math
\text{no bonding}
```

```math
\text{no anti-bonding}
```

```math
\text{no energy splitting}
```

Answer:

```math
\boxed{\text{Isolated atoms keep separate atomic energy levels.}}
```

---

## Example 3: Bonding Orbital Formation

Question:

Why is the bonding orbital written as:

```math
\psi_{\text{bonding}}=\psi_A+\psi_B
```

Answer:

The two atomic wavefunctions are added point by point in space.

If they are in phase:

```math
\psi_A+\psi_B
```

gives constructive interference.

This gives:

```math
\text{larger }|\psi|^2\text{ between nuclei}
```

So electron probability density increases between the two positive nuclei.

This increases attraction:

```math
\text{electron density between nuclei}
\Rightarrow
\text{stronger electron-nucleus attraction}
```

Therefore:

```math
E_{\text{bonding}}<E_{\text{atomic}}
```

Final:

```math
\boxed{\text{Bonding orbital has lower energy because electron density increases between nuclei.}}
```

---

## Example 4: Anti-Bonding Orbital Formation

Question:

Why is the anti-bonding orbital written as:

```math
\psi_{\text{anti-bonding}}=\psi_A-\psi_B
```

Answer:

If two wavefunctions are out of phase, subtracting them causes destructive interference.

Between the nuclei:

```math
\psi_A-\psi_B=0
```

So:

```math
\psi=0
```

and:

```math
|\psi|^2=0
```

This creates a node.

At the node:

```math
\text{no electron density between nuclei}
```

So attraction between electrons and nuclei is weaker.

Therefore:

```math
E_{\text{anti-bonding}}>E_{\text{atomic}}
```

Final:

```math
\boxed{\text{Anti-bonding orbital has higher energy because it has a node between nuclei.}}
```

---

## Example 5: Bonding vs Anti-Bonding Summary

| Type | Wavefunction | Phase | Electron density between nuclei | Energy |
|---|---|---|---|---|
| Bonding | $\psi_A+\psi_B$ | same phase | high | lower |
| Anti-bonding | $\psi_A-\psi_B$ | opposite phase | zero / node | higher |

Memory:

```math
\text{add}
\Rightarrow
\text{bonding}
\Rightarrow
\text{lower energy}
```

```math
\text{subtract}
\Rightarrow
\text{anti-bonding}
\Rightarrow
\text{higher energy}
```

---

## Example 6: Energy Level Splitting in H$_2$

Two H atoms each provide one $1s$ orbital.

So:

```math
2\ \text{atomic orbitals}
\rightarrow
2\ \text{molecular orbitals}
```

These are:

```math
\text{bonding orbital}
```

and:

```math
\text{anti-bonding orbital}
```

Energy order:

```math
E_{\text{bonding}}<E_{1s}<E_{\text{anti-bonding}}
```

For $H_2$, there are two electrons.

They fill the lower-energy bonding orbital first:

```math
2\ \text{electrons}
\rightarrow
\text{bonding orbital filled}
```

```math
\text{anti-bonding orbital empty}
```

Therefore:

```math
\text{total energy decreases}
```

Final:

```math
\boxed{H_2\text{ is stable because the bonding orbital is filled.}}
```

---

## Example 7: From Atomic Levels to Energy Bands

Question:

Why do energy bands form in solids?

Answer:

For $N$ atoms:

```math
N\ \text{atomic orbitals}
\rightarrow
N\ \text{split energy levels}
```

In a solid:

```math
N\sim10^{23}
```

So the split levels are extremely close together.

Therefore:

```math
\text{many closely spaced levels}
\rightarrow
\text{energy band}
```

Final:

```math
\boxed{\text{Energy bands form because many atomic orbitals overlap and split.}}
```

---

## Example 8: Lithium Band Formation

Lithium electron configuration:

```math
1s^2 2s^1
```

For $N$ Li atoms:

### $1s$ band

Each Li atom has:

```math
1s^2
```

So $N$ atoms have:

```math
2N\ \text{1s electrons}
```

The $1s$ band has:

```math
2N\ \text{states}
```

Therefore:

```math
1s\ \text{band is full}
```

---

### $2s$ band

Each Li atom has:

```math
2s^1
```

So $N$ atoms have:

```math
N\ \text{2s electrons}
```

The $2s$ band has:

```math
2N\ \text{states}
```

Therefore:

```math
2s\ \text{band is half-filled}
```

Since the $2s$ band is partially filled:

```math
\text{electrons + nearby empty states}
\Rightarrow
\text{metallic conduction}
```

Final:

```math
\boxed{\text{Lithium conducts because its }2s\text{ band is half-filled.}}
```

---

## Example 9: Full Band vs Partially Filled Band

Question:

Why does a full band not conduct well?

A full band has:

```math
\text{all states occupied}
```

For electron motion, an electron needs a nearby empty state.

But in a full band:

```math
\text{no nearby empty states}
```

Therefore:

```math
\text{poor conduction}
```

For a partially filled band:

```math
\text{electrons}
+
\text{nearby empty states}
```

So electrons can move under an electric field.

Final:

```math
\boxed{\text{Partially filled bands conduct; full bands do not conduct well.}}
```

---

## Example 10: Vacuum Level

Question:

What is the vacuum level?

Answer:

Vacuum level is:

```math
E_{\text{vac}}=\text{energy of an electron just free from the material}
```

If:

```math
E<E_{\text{vac}}
```

then:

```math
\text{electron is bound inside material}
```

If:

```math
E=E_{\text{vac}}
```

then:

```math
\text{electron has just escaped}
```

Short answer:

```math
\boxed{E_{\text{vac}}\text{ is the escape energy level.}}
```

---

## Example 11: Fermi Level at 0 K

Question:

At $0K$, should all electrons be at the lowest energy state?

Answer:

No.

Electrons obey the Pauli exclusion principle.

```math
\text{No two electrons can occupy the same quantum state}
```

So electrons fill available states from the bottom upward.

At $0K$:

```math
E<E_F
\Rightarrow
\text{filled}
```

```math
E>E_F
\Rightarrow
\text{empty}
```

Therefore:

```math
E_F=\text{highest occupied energy level at }0K
```

Final:

```math
\boxed{0K\text{ means no thermal excitation, not all electrons in one lowest state.}}
```

---

## Example 12: Fermi Energy as Maximum Kinetic Energy

In the free-electron model:

```math
E=\frac{p^2}{2m_e}
```

This energy is kinetic energy.

At $0K$, electrons fill all allowed kinetic-energy states up to $E_F$.

So:

```math
E_F=\text{maximum occupied kinetic energy at }0K
```

This does not mean every electron has $E_F$.

It means:

```math
\text{electrons occupy energies from bottom up to }E_F
```

Final:

```math
\boxed{E_F\text{ is the maximum occupied kinetic energy at }0K.}
```

---

## Example 13: Work Function of a Metal

Question:

What is the work function?

Answer:

Work function is:

```math
\Phi=E_{\text{vac}}-E_F
```

Meaning:

```math
\Phi=\text{minimum energy needed to remove an electron from the metal}
```

The electron is removed from the Fermi level, not from the band bottom.

Example:

If:

```math
E_{\text{vac}}=0\ \text{eV}
```

and:

```math
E_F=-4.7\ \text{eV}
```

then:

```math
\Phi=0-(-4.7)=4.7\ \text{eV}
```

Final:

```math
\boxed{\Phi=4.7\ \text{eV}}
```

---

## Example 14: Aluminium Metal Band Diagram

Given:

```math
E_F-E_b=11.6\ \text{eV}
```

and:

```math
\Phi=4.25\ \text{eV}
```

Choose the band bottom as reference:

```math
E_b=0
```

Then:

```math
E_F=11.6\ \text{eV}
```

Work function:

```math
\Phi=E_{\text{vac}}-E_F
```

So:

```math
E_{\text{vac}}=E_F+\Phi
```

Substitute:

```math
E_{\text{vac}}=11.6+4.25
```

```math
E_{\text{vac}}=15.85\ \text{eV}
```

Final labelled diagram values:

```math
\boxed{E_b=0\ \text{eV}}
```

```math
\boxed{E_F=11.6\ \text{eV}}
```

```math
\boxed{E_{\text{vac}}=15.85\ \text{eV}}
```

```math
\boxed{\Phi=4.25\ \text{eV}}
```

---

## Example 15: What Is the Band Bottom $E_b$?

Question:

What exactly is $E_b$?

Answer:

```math
E_b=\text{bottom of the energy band}
```

Meaning:

```math
E_b=\text{lowest allowed energy in that band}
```

If a question says:

```math
E_F=11.6\ \text{eV with respect to band bottom}
```

it means:

```math
E_F-E_b=11.6\ \text{eV}
```

If:

```math
E_b=0
```

then:

```math
E_F=11.6\ \text{eV}
```

Final:

```math
\boxed{E_b\text{ is the lowest allowed energy of the metal band.}}
```

---

## Example 16: Why Metals Do Not Use a Separate $E_C$

In semiconductors:

```math
E_C=\text{bottom of conduction band}
```

```math
E_V=\text{top of valence band}
```

There is a band gap:

```math
E_g=E_C-E_V
```

In metals:

```math
\text{band is partially filled}
```

or:

```math
\text{bands overlap}
```

So there is usually no separate semiconductor-style $E_C$.

Metal conduction comes from:

```math
\text{partially filled band crossing }E_F
```

Final:

```math
\boxed{\text{In metals, the partially filled band itself acts as the conducting band.}}
```

---

## Example 17: Metal-Metal Contact Potential

Given:

```math
\Phi_{\text{Pt}}=5.36\ \text{eV}
```

```math
\Phi_{\text{Mo}}=4.2\ \text{eV}
```

Find contact potential.

Use:

```math
e\Delta V=\Phi_{\text{Pt}}-\Phi_{\text{Mo}}
```

Substitute:

```math
e\Delta V=5.36-4.2
```

```math
e\Delta V=1.16\ \text{eV}
```

Therefore:

```math
\Delta V=1.16\ \text{V}
```

Direction of electron transfer:

Smaller work function means higher Fermi level relative to vacuum.

```math
\Phi_{\text{Mo}}<\Phi_{\text{Pt}}
```

so:

```math
E_F(\text{Mo})>E_F(\text{Pt})
```

Electrons move:

```math
\text{Mo}\rightarrow\text{Pt}
```

Final:

```math
\boxed{\Delta V=1.16\ \text{V}}
```

```math
\boxed{e^-\text{ transfer from Mo to Pt}}
```

---

## Example 18: Aluminium-Lithium Contact Potential

Given:

```math
\Phi_{\text{Al}}\approx4.3\ \text{eV}
```

```math
\Phi_{\text{Li}}=3.0\ \text{eV}
```

Use:

```math
e\Delta V=\Phi_{\text{Al}}-\Phi_{\text{Li}}
```

Substitute:

```math
e\Delta V=4.3-3.0
```

```math
e\Delta V=1.3\ \text{eV}
```

Therefore:

```math
\Delta V=1.3\ \text{V}
```

Because:

```math
\Phi_{\text{Li}}<\Phi_{\text{Al}}
```

then:

```math
E_F(\text{Li})>E_F(\text{Al})
```

Electrons transfer:

```math
\text{Li}\rightarrow\text{Al}
```

Final:

```math
\boxed{\Delta V\approx1.3\ \text{V}}
```

```math
\boxed{e^-\text{ transfer from Li to Al}}
```

---

## Example 19: Reading an $E-k$ Diagram

For a free-electron-like band:

```math
E=\frac{p^2}{2m^*}
```

and:

```math
p=\hbar k
```

So:

```math
E=\frac{\hbar^2k^2}{2m^*}
```

This gives a parabolic $E-k$ diagram.

If the parabola is steep:

```math
\frac{d^2E}{dk^2}\text{ large}
```

then:

```math
m^*=\frac{\hbar^2}{d^2E/dk^2}
```

is small.

Small effective mass means:

```math
\text{carrier accelerates more easily}
```

Final:

```math
\boxed{\text{larger curvature } \Rightarrow \text{ smaller effective mass}}
```

---

## Example 20: Effective Mass and Conductivity

Question:

Why does smaller effective mass usually mean higher conductivity?

Answer:

Carrier mobility roughly follows:

```math
\mu\propto\frac{1}{m^*}
```

So:

```math
m^*\downarrow
\Rightarrow
\mu\uparrow
```

Conductivity depends on mobility:

```math
\sigma=ne\mu
```

or in semiconductors:

```math
\sigma=q(n\mu_n+p\mu_p)
```

Therefore:

```math
m^*\downarrow
\Rightarrow
\mu\uparrow
\Rightarrow
\sigma\uparrow
```

Final:

```math
\boxed{\text{smaller effective mass usually gives higher mobility and higher conductivity.}}
```

---

## Example 21: Origin of Holes

Question:

What is a hole?

Answer:

A hole is:

```math
\text{missing electron in a nearly full valence band}
```

If an electron leaves the valence band, it leaves an empty state.

That empty state behaves like:

```math
\text{positive mobile carrier}
```

So:

```math
\text{electron removed from valence band}
\Rightarrow
\text{hole created}
```

Final:

```math
\boxed{\text{A hole is an empty valence-band state behaving like a positive carrier.}}
```

---

## Example 22: Semiconductor Band Diagram

Given:

```math
E_C=1.0\ \text{eV}
```

```math
E_V=0\ \text{eV}
```

Find band gap.

Use:

```math
E_g=E_C-E_V
```

Substitute:

```math
E_g=1.0-0
```

```math
E_g=1.0\ \text{eV}
```

Final:

```math
\boxed{E_g=1.0\ \text{eV}}
```

---

## Example 23: Electron Affinity

Given:

```math
E_{\text{vac}}=4.5\ \text{eV}
```

```math
E_C=0.4\ \text{eV}
```

Find electron affinity.

Use:

```math
\chi=E_{\text{vac}}-E_C
```

Substitute:

```math
\chi=4.5-0.4
```

```math
\chi=4.1\ \text{eV}
```

Final:

```math
\boxed{\chi=4.1\ \text{eV}}
```

Meaning:

```math
\chi=\text{energy needed to remove an electron from }E_C\text{ to vacuum}
```

---

## Example 24: Work Function vs Electron Affinity

Question:

What is the difference between work function and electron affinity?

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

So:

```math
\Phi\text{ uses }E_F
```

```math
\chi\text{ uses }E_C
```

```math
E_g\text{ uses }E_C\text{ and }E_V
```

Final:

```math
\boxed{\Phi\neq\chi}
```

```math
\boxed{\Phi\text{ measures vacuum to Fermi level; }\chi\text{ measures vacuum to conduction band edge.}}
```

---

## Example 25: Metal vs Semiconductor vs Insulator

Question:

Classify a material from its band structure.

### Case A

Band is partially filled.

```math
\text{partially filled band}
\Rightarrow
\text{metal}
```

Answer:

```math
\boxed{\text{metal}}
```

---

### Case B

Valence band full, conduction band empty, small band gap.

```math
E_g\sim1\ \text{eV}
```

Answer:

```math
\boxed{\text{semiconductor}}
```

---

### Case C

Valence band full, conduction band empty, large band gap.

```math
E_g\sim6\ \text{eV}
```

Answer:

```math
\boxed{\text{insulator}}
```

---

## Example 26: Why Semiconductors Conduct at Room Temperature

At $0K$:

```math
\text{valence band full}
```

```math
\text{conduction band empty}
```

So ideal intrinsic semiconductor has very low conductivity.

At room temperature:

```math
\text{some electrons gain thermal energy}
```

and jump:

```math
E_V\rightarrow E_C
```

This creates:

```math
\text{electron in conduction band}
+
\text{hole in valence band}
```

So current can flow by:

```math
\text{electrons and holes}
```

Final:

```math
\boxed{\text{Semiconductors conduct at room temperature because thermal excitation creates electrons and holes.}}
```

---

## Example 27: Fermi-Dirac Distribution at $T=0K$

At $T=0K$:

```math
f(E)=1\quad E<E_F
```

```math
f(E)=0\quad E>E_F
```

So:

```math
f(E)=\text{step function}
```

At $E=E_F$, from the general formula:

```math
f(E_F)=\frac{1}{2}
```

Final:

```math
\boxed{\text{At }0K,\text{ states below }E_F\text{ are filled and states above are empty.}}
```

---

## Example 28: Electron Distribution $n_E$

Given:

```math
g(E)=\text{available states}
```

and:

```math
f(E)=\text{occupation probability}
```

The electron concentration per unit energy is:

```math
n_E=g(E)f(E)
```

Meaning:

```math
\text{actual electrons}
=
\text{available states}
\times
\text{probability of occupation}
```

At $0K$:

For $E<E_F$:

```math
f(E)=1
```

so:

```math
n_E=g(E)
```

For $E>E_F$:

```math
f(E)=0
```

so:

```math
n_E=0
```

Final:

```math
\boxed{n_E\text{ follows }g(E)\text{ below }E_F\text{ and becomes zero above }E_F.}
```

---

## Example 29: Average Electron Energy

Average electron energy is:

```math
E_{\text{average}}
=
\frac{\int E n_E\,dE}{n}
```

where:

```math
n=\int n_E\,dE
```

For free electrons at $0K$:

```math
E_{\text{average}}\approx\frac{3}{5}E_F
```

Meaning:

```math
E_F=\text{highest occupied energy}
```

but:

```math
E_{\text{average}}=\text{average over all occupied energies}
```

Final:

```math
\boxed{E_{\text{average}}\neq E_F}
```

---

## Example 30: Short Exam-Style Explanation — Metal Conduction

Question:

Why do metals have high conductivity?

Answer:

```text
Metals have partially filled or overlapping energy bands. This means there are occupied electron states close to empty states near the Fermi level. Under an applied electric field, electrons near the Fermi level can move into nearby empty states, producing current. Therefore metals have high electrical conductivity.
```

---

## Example 31: Short Exam-Style Explanation — Semiconductor vs Insulator

Question:

Why does a semiconductor conduct better than an insulator?

Answer:

```text
Both semiconductors and insulators have a full valence band and an empty conduction band at 0 K. However, a semiconductor has a much smaller band gap, typically around 1 eV, so some electrons can be thermally excited into the conduction band at room temperature. This creates mobile electrons and holes. An insulator has a much larger band gap, so almost no carriers are thermally generated.
```

---

## Example 32: Short Exam-Style Explanation — Contact Potential

Question:

Why does a contact potential form between two metals?

Answer:

```text
Two metals can have different work functions and therefore different Fermi levels relative to the vacuum level before contact. When they are brought into contact, electrons transfer from the metal with the higher Fermi level to the metal with the lower Fermi level. This charge transfer creates charge separation and an electric potential difference. Electron transfer continues until the Fermi levels align at equilibrium.
```