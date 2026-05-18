# Electrical and Thermal Conductivity

For worked examples, see:

➡️ [Conductivity Examples](./examples.md)

---

## 1. Core Idea

Electrical conduction:

```math
\text{electric field}
\rightarrow
\text{carrier drift}
\rightarrow
\text{current}
```

Thermal conduction:

```math
\text{temperature difference}
\rightarrow
\text{heat flow}
```

Main idea:

```math
\text{conductivity}
=
\text{how easily charge or heat is transported}
```

---

## 2. Resistance, Resistivity and Conductivity

Resistance:

```math
R=\text{resistance of a specific object}
```

Resistivity:

```math
\rho=\text{material property}
```

Conductivity:

```math
\sigma=\text{ability to conduct current}
```

For a uniform wire:

```math
R=\rho\frac{L}{A}
```

So:

```math
\rho=\frac{RA}{L}
```

Also:

```math
\sigma=\frac{1}{\rho}
```

Therefore:

```math
R=\frac{L}{\sigma A}
```

where:

- $R$: resistance
- $\rho$: resistivity
- $\sigma$: conductivity
- $L$: length
- $A$: cross-sectional area

For circular wire:

```math
A=\pi r^2
```

```math
r=\frac{d}{2}
```

Key effects:

```math
L\uparrow \Rightarrow R\uparrow
```

```math
A\uparrow \Rightarrow R\downarrow
```

```math
\sigma\uparrow \Rightarrow R\downarrow
```

```math
\rho\uparrow \Rightarrow \sigma\downarrow
```

---

## 3. Temperature Effect in Metals

For metals:

```math
T\uparrow
\Rightarrow
\rho\uparrow
```

Reason:

```math
T\uparrow
\Rightarrow
\text{lattice vibration}\uparrow
\Rightarrow
\text{electron scattering}\uparrow
\Rightarrow
\tau\downarrow
\Rightarrow
\mu\downarrow
\Rightarrow
\sigma\downarrow
\Rightarrow
\rho\uparrow
```

Linear approximation:

```math
\rho=AT+B
```

where:

- $A$: positive temperature coefficient
- $B$: residual / baseline resistivity

Exam wording:

```math
\text{higher temperature}
\rightarrow
\text{stronger lattice vibration}
\rightarrow
\text{more electron scattering}
\rightarrow
\text{higher resistivity}
```

---

## 4. Electron Concentration in Metals

Electron concentration:

```math
n=\text{number of conduction electrons per unit volume}
```

Unit:

```math
\text{m}^{-3}
```

If each atom gives one conduction electron:

```math
n=\text{atom concentration}
```

From density and molar mass:

```math
n=
\frac{\text{density}}{\text{molar mass}}N_A
```

Unit logic:

```math
\frac{\text{kg m}^{-3}}{\text{kg mol}^{-1}}
=
\text{mol m}^{-3}
```

```math
\text{mol m}^{-3}\times N_A
=
\text{atoms m}^{-3}
```

If:

```math
1\ \text{atom}
\rightarrow
1\ \text{conduction electron}
```

then:

```math
\text{atoms m}^{-3}
=
\text{electrons m}^{-3}
```

---

## 5. Mobility and Drift Velocity

Mobility:

```math
\mu=\text{how easily carriers drift under an electric field}
```

Definition:

```math
v_d=\mu E
```

where:

- $v_d$: drift velocity
- $E$: electric field
- $\mu$: mobility

Meaning:

```math
\mu\uparrow
\Rightarrow
\text{larger drift velocity for same electric field}
```

For metal electrons:

```math
\sigma=ne\mu
```

Using:

```math
\sigma=\frac{1}{\rho}
```

gives:

```math
\mu=\frac{1}{ne\rho}
```

Current density:

```math
J=\frac{I}{A}
```

For electrons:

```math
J=nev_{\text{drift}}
```

So:

```math
v_{\text{drift}}=\frac{J}{ne}
```

Important idea:

```math
\text{random electron speed can be large}
```

but:

```math
\text{average drift velocity is usually small}
```

---

## 6. Drude Model and Scattering Time

Scattering / relaxation time:

```math
\tau=\text{average time between scattering events}
```

Scattering sources:

```math
\text{lattice vibrations}
```

```math
\text{impurities}
```

```math
\text{defects}
```

Drude mobility:

```math
\mu_{\text{drift}}=\frac{e\tau}{m^*}
```

If:

```math
m^*=m_e
```

then:

```math
\mu_{\text{drift}}=\frac{e\tau}{m_e}
```

Rearrange:

```math
\tau=\frac{\mu m_e}{e}
```

Drude conductivity:

```math
\sigma=ne\mu_{\text{drift}}
```

Substitute mobility:

```math
\sigma=\frac{ne^2\tau}{m_e}
```

Key trends:

```math
n\uparrow \Rightarrow \sigma\uparrow
```

```math
\tau\uparrow \Rightarrow \mu\uparrow \Rightarrow \sigma\uparrow \Rightarrow \rho\downarrow
```

```math
\tau\downarrow
\Rightarrow
\text{more scattering}
\Rightarrow
\rho\uparrow
```

---

## 7. Current and Ohm's Law

Ohm's law:

```math
I=\frac{V}{R}
```

where:

- $I$: current
- $V$: applied voltage
- $R$: resistance

Current density:

```math
J=\frac{I}{A}
```

Drift velocity:

```math
v_{\text{drift}}=\frac{J}{ne}
```

---

## 8. Einstein Relation and Diffusion

Diffusion coefficient:

```math
D=\text{how easily carriers spread by diffusion}
```

Einstein relation:

```math
D=\frac{\mu k_BT}{e}
```

where:

- $D$: diffusion coefficient
- $\mu$: mobility
- $k_B$: Boltzmann constant
- $T$: absolute temperature
- $e$: electron charge magnitude

Drift:

```math
\text{electric field}
\rightarrow
\text{carrier drift}
```

Diffusion:

```math
\text{concentration gradient}
\rightarrow
\text{carrier spreading}
```

Key trends:

```math
\mu\uparrow \Rightarrow D\uparrow
```

```math
T\uparrow \Rightarrow D\uparrow
```

---

## 9. Thermal Conductivity and Thermal Resistance

Thermal conductivity:

```math
\kappa=\text{ability to conduct heat}
```

Unit:

```math
\text{W m}^{-1}\text{K}^{-1}
```

Meaning:

```math
\kappa\uparrow
\Rightarrow
\text{heat flows more easily}
```

Thermal resistance:

```math
\theta=\frac{\Delta T}{P}
```

where:

- $\theta$: thermal resistance
- $\Delta T$: temperature drop
- $P$: heat flow rate / thermal power

For a uniform rod or wire:

```math
\theta=\frac{L}{\kappa A}
```

Temperature drop:

```math
\Delta T=P\theta
```

Key effects:

```math
L\uparrow \Rightarrow \theta\uparrow
```

```math
A\uparrow \Rightarrow \theta\downarrow
```

```math
\kappa\uparrow \Rightarrow \theta\downarrow
```

---

## 10. Electrical and Thermal Analogy

| Electrical | Thermal |
|---|---|
| voltage difference $V$ | temperature difference $\Delta T$ |
| current $I$ | heat flow rate $P$ |
| resistance $R$ | thermal resistance $\theta$ |
| resistivity $\rho$ | thermal resistivity $1/\kappa$ |
| conductivity $\sigma$ | thermal conductivity $\kappa$ |

Electrical:

```math
R=\rho\frac{L}{A}
```

Thermal:

```math
\theta=\frac{L}{\kappa A}
```

---

## 11. Semiconductor Conductivity

In semiconductors, current can come from:

```math
\text{electrons in conduction band}
```

and:

```math
\text{holes in valence band}
```

Conductivity:

```math
\sigma=ne\mu_e+pe\mu_h
```

where:

- $n$: electron concentration
- $p$: hole concentration
- $\mu_e$: electron mobility
- $\mu_h$: hole mobility

Meaning:

```math
\text{conductivity}
=
\text{electron contribution}
+
\text{hole contribution}
```

Important:

```math
\text{high mobility}
\neq
\text{always high conductivity}
```

because conductivity also depends on:

```math
n,\quad p
```

---

## 12. Hole

A hole is:

```math
\text{missing electron in the valence band}
```

It behaves like:

```math
\text{positive mobile charge carrier}
```

Formation:

```math
\text{electron leaves valence band}
\Rightarrow
\text{empty state left behind}
\Rightarrow
\text{hole}
```

Electron-hole pair:

```math
\text{electron in conduction band}
+
\text{hole in valence band}
```

---

## 13. Intrinsic Semiconductor

Intrinsic semiconductor:

```math
\text{pure semiconductor with no intentional doping}
```

Examples:

```math
\text{pure Si},\quad \text{pure Ge}
```

Carriers come from thermal excitation:

```math
\text{thermal energy}
\rightarrow
\text{electron jumps from valence band to conduction band}
\rightarrow
e^-+h^+
```

For intrinsic material:

```math
n=p=n_i
```

where:

```math
n_i=\text{intrinsic carrier concentration}
```

Key result:

```math
n_i\text{ low}
\Rightarrow
\sigma\text{ low}
```

---

## 14. Doping and Extrinsic Semiconductors

Doping:

```math
\text{intentional addition of impurity atoms}
```

Purpose:

```math
\text{increase electron or hole concentration}
```

Therefore:

```math
\text{doping}
\Rightarrow
n\text{ or }p\text{ increases}
\Rightarrow
\sigma\text{ increases / becomes controllable}
```

Extrinsic semiconductor:

```math
\text{doped semiconductor}
```

Meaning:

```math
\text{carrier concentration is controlled by dopants}
```

---

## 15. n-Type Semiconductor

n-type:

```math
\text{donor-doped semiconductor}
```

For silicon, donor dopants are Group V atoms:

```math
P,\ As,\ Sb
```

In Si lattice:

```math
4\ \text{electrons form bonds}
```

```math
1\ \text{extra electron becomes mobile}
```

So:

```math
\text{donor}
\rightarrow
\text{extra electron}
\rightarrow
\text{n-type}
```

Carrier relation:

```math
n\gg p
```

Majority carriers:

```math
\text{electrons}
```

---

## 16. p-Type Semiconductor

p-type:

```math
\text{acceptor-doped semiconductor}
```

For silicon, acceptor dopants are Group III atoms:

```math
B,\ Al,\ Ga
```

In Si lattice:

```math
\text{one bond lacks an electron}
```

This creates:

```math
\text{hole}
```

So:

```math
\text{acceptor}
\rightarrow
\text{hole}
\rightarrow
\text{p-type}
```

Carrier relation:

```math
p\gg n
```

Majority carriers:

```math
\text{holes}
```

---

## 17. Intrinsic vs Extrinsic

| Type | Meaning | Carrier source | Carrier relation |
|---|---|---|---|
| Intrinsic | pure semiconductor | thermal excitation | $n=p=n_i$ |
| n-type extrinsic | donor-doped | extra electrons | $n\gg p$ |
| p-type extrinsic | acceptor-doped | extra holes | $p\gg n$ |

Key memory:

```math
\text{intrinsic}=\text{pure, few carriers}
```

```math
\text{extrinsic}=\text{doped, controlled carriers}
```

```math
\text{n-type}=\text{extra electrons}
```

```math
\text{p-type}=\text{extra holes}
```

---

## 18. Effective Mass and Conductivity

Effective mass:

```math
m^*=\text{carrier inertia inside a crystal}
```

Smaller effective mass:

```math
m^*\downarrow
\Rightarrow
\mu\uparrow
```

Mobility trend:

```math
\mu\propto\frac{1}{m^*}
```

For semiconductors:

```math
\sigma=ne\mu_e+pe\mu_h
```

If carrier concentrations and scattering times are assumed similar:

```math
\sigma\propto
\frac{1}{m_e^*}
+
\frac{1}{m_h^*}
```

Use:

```math
\frac{1}{m_e^*}+\frac{1}{m_h^*}
```

as a simple mobility / conductivity trend indicator.

---

## 19. Direct and Indirect Bandgap

In an $E-k$ diagram:

```math
p=\hbar k
```

So $k$ relates to crystal momentum.

---

### 19.1 Direct Bandgap

Direct bandgap:

```math
\text{conduction band minimum and valence band maximum occur at same }k
```

Meaning:

```math
\Delta k\approx0
```

Electron can recombine with hole without large momentum change.

So:

```math
\text{direct bandgap}
\Rightarrow
\text{efficient photon emission}
```

Good for:

```math
\text{LEDs, lasers, optical emitters}
```

---

### 19.2 Indirect Bandgap

Indirect bandgap:

```math
\text{conduction band minimum and valence band maximum occur at different }k
```

Meaning:

```math
\Delta k\neq0
```

Photon carries very little momentum, so phonon assistance is needed.

```math
\text{indirect bandgap}
\Rightarrow
\text{inefficient light emission}
```

Examples:

```math
\text{Si, Ge}
```

---

## 20. Bandgap and Emitted Wavelength

Radiative recombination:

```math
E_{\text{photon}}\approx E_g
```

Photon energy:

```math
E=\frac{hc}{\lambda}
```

Useful form:

```math
E(\text{eV})=\frac{1240}{\lambda(\text{nm})}
```

So:

```math
\lambda(\text{nm})=\frac{1240}{E_g(\text{eV})}
```

Key trend:

```math
E_g\downarrow
\Rightarrow
\lambda\uparrow
```

```math
E_g\uparrow
\Rightarrow
\lambda\downarrow
```

---

## 21. Silicon vs Gallium Arsenide

Under simplified physics:

```math
\text{GaAs}
\Rightarrow
\text{higher mobility}
+
\text{direct bandgap}
```

So GaAs is good for:

```math
\text{high-speed electronics}
```

```math
\text{optoelectronics}
```

Silicon:

```math
\text{indirect bandgap}
\Rightarrow
\text{poor light emitter}
```

Intrinsic silicon:

```math
\text{low carrier concentration}
\Rightarrow
\text{low conductivity}
```

Real silicon devices use extrinsic silicon:

```math
\text{doping}
\Rightarrow
\text{controlled }n\text{ or }p
```

Silicon is widely used because:

```math
\text{cheap and abundant}
```

```math
\text{mature fabrication}
```

```math
\text{good control of electronic properties}
```

```math
\text{high-quality }SiO_2
```

```math
\text{cheap and efficient manufacturing}
```

Key conclusion:

```math
\text{GaAs wins in mobility / optics}
```

but:

```math
\text{Si wins in manufacturing and controllability}
```

---

## 22. Metal Energy Band Diagram

For a metal energy band diagram:

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

---

### 22.1 Band Bottom $E_b$

Band bottom:

```math
E_b=\text{lowest allowed energy in the metal band}
```

or:

```math
E_b=\text{starting point of the metal energy band}
```

If the band bottom is chosen as zero:

```math
E_b=0
```

then all other energies are measured upward from $E_b$.

Example:

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

Meaning:

```math
\text{Fermi level is 11.6 eV above the band bottom}
```

---

### 22.2 Metal Conducting Band

In a semiconductor:

```math
E_C=\text{bottom of conduction band}
```

and:

```math
E_V=\text{top of valence band}
```

There is a band gap:

```math
E_g=E_C-E_V
```

In a metal:

```math
\text{partially filled band}
```

or:

```math
\text{overlapping bands}
```

So there is usually no separate semiconductor-style $E_C$.

For a metal:

```math
\text{conducting band}
=
\text{partially filled band crossing }E_F
```

The important energy is:

```math
E_F
```

because conduction mainly involves electrons near $E_F$.

Key idea:

```math
\text{occupied states near }E_F
+
\text{nearby empty states}
\Rightarrow
\text{electrons can move}
\Rightarrow
\text{metal conducts}
```

---

### 22.3 Vacuum Level and Work Function

Work function:

```math
\Phi=E_{\text{vac}}-E_F
```

So:

```math
E_{\text{vac}}=E_F+\Phi
```

Meaning:

```math
\Phi=\text{minimum energy needed to remove an electron from }E_F\text{ to vacuum}
```

Short memory:

```math
\Phi=\text{escape energy from }E_F
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

---

## 23. Metal-Metal Contact

When two different metals contact, electrons transfer because their initial Fermi levels differ.

Key rule:

```math
\text{smaller work function}
\Rightarrow
\text{higher Fermi level relative to vacuum}
```

Electrons move from:

```math
\text{higher }E_F
\rightarrow
\text{lower }E_F
```

until equilibrium.

At equilibrium:

```math
E_F\text{ aligns}
```

Charge separation creates:

```math
\text{contact potential}
```

---

## 24. Contact Potential

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

For Aluminium and Lithium:

```math
\Phi_{\text{Al}}\approx4.25\text{--}4.3\ \text{eV}
```

```math
\Phi_{\text{Li}}=3.0\ \text{eV}
```

So:

```math
\Phi_{\text{Al}}-\Phi_{\text{Li}}
\approx1.3\ \text{eV}
```

Therefore:

```math
\Delta V\approx1.3\ \text{V}
```

Logic:

```math
\Phi_{\text{Li}}<\Phi_{\text{Al}}
```

```math
\Rightarrow
E_F(\text{Li})>E_F(\text{Al})
```

```math
\Rightarrow
e^-\text{ transfer from Li to Al}
```

```math
\Rightarrow
\text{charge separation}
```

```math
\Rightarrow
\text{contact potential}
```

```math
\Rightarrow
E_F\text{ alignment}
```

---

## 25. Key Formula Chain

Electrical resistivity:

```math
\rho=\frac{RA}{L}
```

Conductivity:

```math
\sigma=\frac{1}{\rho}
```

Resistance from conductivity:

```math
R=\frac{L}{\sigma A}
```

Metal electron concentration:

```math
n=\frac{\text{density}}{\text{molar mass}}N_A
```

Metal mobility:

```math
\mu=\frac{1}{ne\rho}
```

Drude mobility:

```math
\mu=\frac{e\tau}{m_e}
```

Drude conductivity:

```math
\sigma=\frac{ne^2\tau}{m_e}
```

Scattering time:

```math
\tau=\frac{\mu m_e}{e}
```

Current:

```math
I=\frac{V}{R}
```

Current density:

```math
J=\frac{I}{A}
```

Drift velocity:

```math
v_{\text{drift}}=\frac{J}{ne}
```

Einstein relation:

```math
D=\frac{\mu k_BT}{e}
```

Thermal resistance:

```math
\theta=\frac{L}{\kappa A}
```

Temperature drop:

```math
\Delta T=P\theta
```

Semiconductor conductivity:

```math
\sigma=ne\mu_e+pe\mu_h
```

Radiative wavelength:

```math
\lambda(\text{nm})=\frac{1240}{E_g(\text{eV})}
```

Work function:

```math
\Phi=E_{\text{vac}}-E_F
```

Vacuum level:

```math
E_{\text{vac}}=E_F+\Phi
```

Contact potential:

```math
e\Delta V=\Delta\Phi
```