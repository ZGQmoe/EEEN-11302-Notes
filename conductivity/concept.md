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

Semiconductor current can come from:

```math
\text{drift current}
+
\text{diffusion current}
```

Main idea:

```math
\text{conductivity}
=
\text{how easily charge or heat is transported}
```

---

# Part A: Metal and General Conductivity

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

Unit:

```math
\mu:\ \text{m}^2\text{V}^{-1}\text{s}^{-1}
```

or:

```math
\mu:\ \text{cm}^2\text{V}^{-1}\text{s}^{-1}
```

Conversion:

```math
1\ \text{m}^2\text{V}^{-1}\text{s}^{-1}
=
10^4\ \text{cm}^2\text{V}^{-1}\text{s}^{-1}
```

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

Important unit note:

```math
e:\ \text{C}
```

```math
\tau:\ \text{s}
```

```math
m_e:\ \text{kg}
```

Using SI units in $\mu=e\tau/m_e$ gives:

```math
\mu:\ \text{m}^2\text{V}^{-1}\text{s}^{-1}
```

Convert to $\text{cm}^2\text{V}^{-1}\text{s}^{-1}$ at the end if needed.

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

# Part B: Diffusion, Drift and Semiconductor Conductivity

## 8. Drift Current in Semiconductors

Drift means carrier motion caused by an electric field.

Electron drift velocity:

```math
v_{de}=\mu_{de}E
```

Hole drift velocity:

```math
v_{dh}=\mu_{dh}E
```

Drude model is valid for both electron and hole motion:

```math
\mu_{de}=\frac{e\tau}{m_e^*}
```

```math
\mu_{dh}=\frac{e\tau}{m_h^*}
```

where:

- $\mu_{de}$: electron drift mobility
- $\mu_{dh}$: hole drift mobility
- $m_e^*$: electron effective mass
- $m_h^*$: hole effective mass

Semiconductor conductivity:

```math
\sigma=ne\mu_{de}+pe\mu_{dh}
```

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

## 9. Hole

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

## 10. Intrinsic Semiconductor

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

## 11. Doping and Extrinsic Semiconductors

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

## 12. n-Type Semiconductor

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

For n-type:

```math
n\approx N_D^+
```

Minority hole concentration:

```math
p=\frac{n_i^2}{N_D^+}
```

Full conductivity:

```math
\sigma=N_D^+e\mu_{de}
+
\frac{n_i^2}{N_D^+}e\mu_{dh}
```

Since electrons dominate:

```math
\sigma\approx N_D^+e\mu_{de}
```

---

## 13. p-Type Semiconductor

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

For p-type:

```math
p\approx N_A^-
```

Minority electron concentration:

```math
n=\frac{n_i^2}{N_A^-}
```

Full conductivity:

```math
\sigma=
\frac{n_i^2}{N_A^-}e\mu_{de}
+
N_A^-e\mu_{dh}
```

Since holes dominate:

```math
\sigma\approx N_A^-e\mu_{dh}
```

---

## 14. Intrinsic vs Extrinsic

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

## 15. Diffusion Current

Diffusion is caused by concentration gradients.

```math
\text{high carrier concentration}
\rightarrow
\text{low carrier concentration}
```

Diffusion coefficient:

```math
D=\text{how easily carriers spread by diffusion}
```

Electron diffusion current density:

```math
J_{D,e}=eD_e\frac{dn}{dx}
```

Hole diffusion current density:

```math
J_{D,h}=-eD_h\frac{dp}{dx}
```

where:

- $D_e$: electron diffusion coefficient
- $D_h$: hole diffusion coefficient
- $n$: electron concentration
- $p$: hole concentration

Key sign idea:

```math
\text{conventional current direction}
\neq
\text{electron motion direction}
```

Conventional current is defined as positive charge flow.

---

## 16. Einstein Relation

Diffusion coefficient and mobility are directly related.

Electron:

```math
D_e=\frac{k_BT}{e}\mu_e
```

Hole:

```math
D_h=\frac{k_BT}{e}\mu_h
```

General form:

```math
D=\frac{\mu k_BT}{e}
```

where:

- $D$: diffusion coefficient
- $\mu$: mobility
- $k_B$: Boltzmann constant
- $T$: absolute temperature
- $e$: electron charge magnitude

At room temperature:

```math
\frac{k_BT}{e}\approx0.0259\ \text{V}
```

So:

```math
D\approx0.0259\mu
```

if $\mu$ is in $\text{m}^2\text{V}^{-1}\text{s}^{-1}$, then $D$ is in $\text{m}^2\text{s}^{-1}$.

If $\mu$ is in $\text{cm}^2\text{V}^{-1}\text{s}^{-1}$, then $D$ is in $\text{cm}^2\text{s}^{-1}$.

Key trends:

```math
\mu\uparrow \Rightarrow D\uparrow
```

```math
T\uparrow \Rightarrow D\uparrow
```

---

## 17. Diffusion vs Drift

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

Total electron current:

```math
J_e=J_{\text{drift},e}+J_{D,e}
```

Total hole current:

```math
J_h=J_{\text{drift},h}+J_{D,h}
```

If light generates electron-hole pairs near one side:

```math
\text{light}
\rightarrow
e^-+h^+
```

then both drift and diffusion may appear.

Exam memory:

```math
\text{drift}
\Rightarrow
\text{electric field driven}
```

```math
\text{diffusion}
\Rightarrow
\text{concentration-gradient driven}
```

---

## 18. Temperature Dependence and Impurity Engineering

There are three temperature regions.

### 18.1 Ionisation Range: Low Temperature

At low temperature:

```math
\text{not all dopants ionised}
```

As temperature increases:

```math
T\uparrow
\Rightarrow
\text{more donors ionised}
\Rightarrow
n\uparrow
```

Electron concentration increases until saturation temperature $T_s$.

---

### 18.2 Extrinsic Range: Medium Temperature

In the extrinsic range:

```math
\text{all donors ionised}
```

For n-type:

```math
n=N_D
```

Carrier concentration is approximately constant.

This is useful because:

```math
\text{carrier concentration controlled by doping}
```

---

### 18.3 Intrinsic Range: High Temperature

At high temperature:

```math
\text{thermal excitation generates electron-hole pairs}
```

So:

```math
n\uparrow,\quad p\uparrow
```

Conductivity increases strongly.

---

## 19. Mobility vs Temperature

Low-temperature impurity scattering:

```math
\mu\propto T^{3/2}
```

High-temperature lattice scattering:

```math
\mu\propto T^{-3/2}
```

Meaning:

```math
\text{low }T:
\text{ increasing }T\text{ reduces impurity scattering effect}
```

```math
\text{high }T:
\text{ lattice vibrations increase}
\Rightarrow
\mu\downarrow
```

---

## 20. Semiconductor vs Metal Temperature Trend

Metal:

```math
T\uparrow
\Rightarrow
\text{lattice scattering}\uparrow
\Rightarrow
\rho\uparrow
```

Semiconductor:

```math
T\uparrow
\Rightarrow
\text{carrier concentration}\uparrow
\Rightarrow
\sigma\uparrow
\Rightarrow
\rho\downarrow
```

Key exam phrase:

```math
\text{In semiconductors, carrier concentration increase can dominate over mobility decrease.}
```

---

## 21. Effective Mass and Conductivity

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

# Part C: p-n Junctions

## 22. p-n Junction Formation

A p-n junction forms when:

```math
p\text{-type semiconductor}
+
n\text{-type semiconductor}
```

are brought into contact.

Carrier diffusion occurs because of concentration gradients.

Electrons diffuse:

```math
n\text{-side}
\rightarrow
p\text{-side}
```

Holes diffuse:

```math
p\text{-side}
\rightarrow
n\text{-side}
```

Diffused carriers recombine near the junction.

This exposes fixed ions:

```math
\text{positive donor ions on n-side}
```

```math
\text{negative acceptor ions on p-side}
```

This forms the depletion region.

---

## 23. Depletion Region

Depletion region:

```math
\text{region near junction depleted of mobile carriers}
```

It contains fixed ionised dopants:

```math
n\text{-side}:\quad +eN_D
```

```math
p\text{-side}:\quad -eN_A
```

Charge neutrality requires:

```math
N_DW_n=N_AW_p
```

Meaning:

```math
\text{total positive charge}
=
\text{total negative charge}
```

If one side is more heavily doped:

```math
\text{depletion width mainly extends into the more lightly doped side}
```

---

## 24. Built-in Electric Field

Fixed charges create a built-in electric field.

Electric field direction:

```math
n\text{-side}
\rightarrow
p\text{-side}
```

Reason:

```math
\text{electric field points from positive donor ions to negative acceptor ions}
```

The built-in field opposes further diffusion.

At equilibrium:

```math
\text{diffusion current}
+
\text{drift current}
=
0
```

---

## 25. Built-in Potential

Built-in potential:

```math
V_0=
\frac{k_BT}{e}
\ln\left(
\frac{N_A N_D}{n_i^2}
\right)
```

where:

- $V_0$: built-in potential
- $N_A$: acceptor concentration
- $N_D$: donor concentration
- $n_i$: intrinsic carrier concentration
- $T$: temperature

Key trends:

```math
N_A,N_D\uparrow
\Rightarrow
V_0\uparrow
```

```math
n_i\uparrow
\Rightarrow
V_0\downarrow
```

---

## 26. Depletion Width at Open Circuit

Total depletion width:

```math
W_0=W_p+W_n
```

Formula:

```math
W_0=
\left[
\frac{2\epsilon}{e}
\frac{N_A+N_D}{N_A N_D}
V_0
\right]^{1/2}
```

where:

```math
\epsilon=\epsilon_0\epsilon_r
```

For an abrupt asymmetric junction:

```math
N_DW_n=N_AW_p
```

So:

```math
\frac{W_p}{W_n}=\frac{N_D}{N_A}
```

The depletion region extends more into the lightly doped side.

---

## 27. Band Diagram in Open Circuit

Before contact:

```math
E_F\text{ differs between p-side and n-side}
```

After contact at equilibrium:

```math
E_F\text{ aligns}
```

Electrons move:

```math
\text{high Fermi level}
\rightarrow
\text{low Fermi level}
```

For p-n junction:

```math
e^-\text{ diffuse from n-type to p-type}
```

Holes move:

```math
p\text{-type}
\rightarrow
n\text{-type}
```

Built-in potential energy:

```math
eV_0=\Phi_p-\Phi_n
```

Meaning:

```math
eV_0=\text{initial Fermi level difference}
```

---

# Part D: Biasing a p-n Junction

## 28. Forward Bias

Forward bias means the applied field is opposite to the built-in field.

Effect:

```math
\text{potential barrier decreases}
```

```math
V_{\text{barrier}}=V_0-V
```

Depletion width:

```math
W=
\left[
\frac{2\epsilon}{e}
\frac{N_A+N_D}{N_A N_D}
(V_0-V)
\right]^{1/2}
```

So:

```math
V\uparrow
\Rightarrow
W\downarrow
```

Result:

```math
\text{depletion region narrows}
```

```math
\text{current can flow}
```

---

## 29. Reverse Bias

Reverse bias means the applied field is in the same direction as the built-in field.

Effect:

```math
\text{potential barrier increases}
```

```math
V_{\text{barrier}}=V_0+V
```

Depletion width:

```math
W=
\left[
\frac{2\epsilon}{e}
\frac{N_A+N_D}{N_A N_D}
(V_0+V)
\right]^{1/2}
```

So:

```math
V\uparrow
\Rightarrow
W\uparrow
```

Result:

```math
\text{depletion region widens}
```

```math
\text{current is strongly blocked}
```

---

## 30. Minority Carrier Injection

Under forward bias:

```math
\text{electrons injected into p-side}
```

```math
\text{holes injected into n-side}
```

These are minority carriers in the opposite region.

They diffuse away from the junction and can recombine.

This minority carrier diffusion gives diode current.

---

## 31. Ideal Diode Equation

Ideal diode current density:

```math
J=J_s\left[
\exp\left(\frac{eV}{k_BT}\right)-1
\right]
```

where:

- $J_s$: saturation current density
- $V$: applied voltage
- $T$: temperature

This ideal form assumes diffusion current only.

---

## 32. Diffusion Current Density in a Diode

Minority carrier diffusion current density:

```math
J_D=
\left[
\frac{eD_h n_i^2}{L_hN_D}
+
\frac{eD_e n_i^2}{L_eN_A}
\right]
\left[
\exp\left(\frac{eV}{k_BT}\right)-1
\right]
```

where:

- $L_e,L_h$: electron/hole diffusion lengths
- $D_e,D_h$: electron/hole diffusion coefficients
- $N_D,N_A$: donor/acceptor concentrations

Key idea:

```math
J_s\propto n_i^2
```

So materials with larger bandgap usually have smaller $n_i$ and need higher voltage for current.

---

## 33. Real Diode Equation and Ideality Factor

Including recombination current:

```math
J=J_0\exp\left(\frac{eV}{\eta k_BT}\right)
```

where:

- $\eta$: ideality factor

Interpretation:

```math
\eta=1
\Rightarrow
\text{minority carrier diffusion dominates}
```

```math
\eta=2
\Rightarrow
\text{recombination dominates}
```

---

## 34. I-V Characteristics

Forward bias:

```math
V>0
\Rightarrow
I\text{ increases exponentially}
```

Reverse bias:

```math
V<0
\Rightarrow
I\approx -I_s
```

Real reverse current can be larger because of:

```math
\text{space charge generation}
```

```math
\text{surface leakage current}
```

---

## 35. Bandgap and Forward Voltage

Forward current depends on:

```math
J_s\propto n_i^2
```

and:

```math
n_i\text{ depends strongly on }E_g
```

Higher bandgap:

```math
E_g\uparrow
\Rightarrow
n_i\downarrow
\Rightarrow
J_s\downarrow
\Rightarrow
\text{higher forward voltage needed}
```

Example trend:

```math
\text{Ge} < \text{Si} < \text{GaAs}
```

in forward voltage.

---

## 36. Avalanche Breakdown

At large reverse bias:

```math
\text{electric field becomes very strong}
```

Electrons gain enough kinetic energy to ionise atoms by collision.

```math
\text{impact ionisation}
\rightarrow
\text{more carriers}
\rightarrow
\text{large reverse current}
```

This is avalanche breakdown.

---

## 37. Zener Breakdown

At very large reverse field and very narrow depletion width:

```math
\text{band bending becomes very strong}
```

Electrons can tunnel through the barrier.

```math
\text{valence band}
\rightarrow
\text{conduction band}
```

This tunnelling gives current.

Zener breakdown is common in heavily doped junctions because:

```math
\text{heavy doping}
\Rightarrow
\text{narrow depletion region}
\Rightarrow
\text{strong electric field}
```

---

# Part E: Applications

## 38. LED

LED works under forward bias.

Forward bias injects minority carriers:

```math
e^-\text{ injected into p-side}
```

```math
h^+\text{ injected into n-side}
```

Electrons recombine with holes and emit photons:

```math
e^-+h^+
\rightarrow
\text{photon}
```

Photon energy:

```math
E_{\text{photon}}\approx E_g
```

Wavelength:

```math
\lambda(\text{nm})=\frac{1240}{E_g(\text{eV})}
```

This is injection electroluminescence.

Important design point:

```math
\text{thin emitting layer}
\Rightarrow
\text{photons can escape before reabsorption}
```

---

## 39. Direct and Indirect Bandgap

In an $E-k$ diagram:

```math
p=\hbar k
```

So $k$ relates to crystal momentum.

Direct bandgap:

```math
\text{conduction band minimum and valence band maximum occur at same }k
```

Meaning:

```math
\Delta k\approx0
```

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

Indirect bandgap:

```math
\text{conduction band minimum and valence band maximum occur at different }k
```

Meaning:

```math
\Delta k\neq0
```

Photon carries little momentum, so phonon assistance is needed.

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

## 40. Bandgap and Emitted Wavelength

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

or:

```math
\lambda(\mu\text{m})=\frac{1.24}{E_g(\text{eV})}
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

## 41. Solar Cell

A solar cell is a p-n junction under illumination.

Light generates electron-hole pairs:

```math
\text{photon}
\rightarrow
e^-+h^+
```

Built-in field separates carriers:

```math
e^-\rightarrow n\text{-side}
```

```math
h^+\rightarrow p\text{-side}
```

This produces photocurrent.

Photocurrent direction:

```math
n\rightarrow p
```

Solar cell current equation:

```math
I=
-I_{\text{ph}}
+
I_0
\left[
\exp\left(\frac{eV}{\eta k_BT}\right)-1
\right]
```

where:

- $I_{\text{ph}}$: photocurrent
- $I_0$: diode saturation current
- $\eta$: ideality factor

---

## 42. Solar Cell I-V Characteristics

Short-circuit condition:

```math
V=0
```

```math
I_{sc}=-I_{\text{ph}}
```

Open-circuit condition:

```math
I=0
```

At open circuit:

```math
\text{diode current}=\text{photocurrent}
```

Open-circuit voltage:

```math
V_{oc}
```

---

## 43. Load Line

For a load resistor:

```math
V=IR
```

In solar-cell convention, load line slope:

```math
\text{slope}=-\frac{1}{R}
```

Operating point:

```math
\text{intersection of solar-cell I-V curve and load line}
```

At the operating point:

```math
\text{solar cell and resistor have same }V\text{ and }I
```

---

## 44. Solar Cell Power and Fill Factor

Power delivered:

```math
P=IV
```

Maximum power point:

```math
P_{\max}=I_mV_m
```

Fill factor:

```math
FF=\frac{I_mV_m}{I_{sc}V_{oc}}
```

where:

- $I_m$: current at maximum power point
- $V_m$: voltage at maximum power point
- $I_{sc}$: short-circuit current
- $V_{oc}$: open-circuit voltage

Meaning:

```math
FF=\text{how rectangular / ideal the solar cell I-V curve is}
```

---

## 45. Silicon vs Gallium Arsenide

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

# Part F: Thermal Conductivity

## 46. Thermal Conductivity and Thermal Resistance

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

## 47. Electrical and Thermal Analogy

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

## 48. Key Formula Chain

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
\mu=\frac{e\tau}{m^*}
```

Drude conductivity:

```math
\sigma=\frac{ne^2\tau}{m^*}
```

Scattering time:

```math
\tau=\frac{\mu m^*}{e}
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

Semiconductor conductivity:

```math
\sigma=ne\mu_e+pe\mu_h
```

n-type conductivity:

```math
\sigma\approx N_D^+e\mu_{de}
```

p-type conductivity:

```math
\sigma\approx N_A^-e\mu_{dh}
```

Electron diffusion current:

```math
J_{D,e}=eD_e\frac{dn}{dx}
```

Hole diffusion current:

```math
J_{D,h}=-eD_h\frac{dp}{dx}
```

Einstein relation:

```math
D=\frac{\mu k_BT}{e}
```

Built-in potential:

```math
V_0=
\frac{k_BT}{e}
\ln\left(
\frac{N_A N_D}{n_i^2}
\right)
```

Open-circuit depletion width:

```math
W_0=
\left[
\frac{2\epsilon}{e}
\frac{N_A+N_D}{N_A N_D}
V_0
\right]^{1/2}
```

Forward-bias depletion width:

```math
W=
\left[
\frac{2\epsilon}{e}
\frac{N_A+N_D}{N_A N_D}
(V_0-V)
\right]^{1/2}
```

Reverse-bias depletion width:

```math
W=
\left[
\frac{2\epsilon}{e}
\frac{N_A+N_D}{N_A N_D}
(V_0+V)
\right]^{1/2}
```

Ideal diode equation:

```math
J=J_s
\left[
\exp\left(\frac{eV}{k_BT}\right)-1
\right]
```

Real diode low-bias equation:

```math
J=J_0
\exp\left(\frac{eV}{\eta k_BT}\right)
```

Solar cell equation:

```math
I=
-I_{\text{ph}}
+
I_0
\left[
\exp\left(\frac{eV}{\eta k_BT}\right)-1
\right]
```

LED / radiative wavelength:

```math
\lambda(\text{nm})=\frac{1240}{E_g(\text{eV})}
```

```math
\lambda(\mu\text{m})=\frac{1.24}{E_g(\text{eV})}
```

Thermal resistance:

```math
\theta=\frac{L}{\kappa A}
```

Temperature drop:

```math
\Delta T=P\theta
```

Fill factor:

```math
FF=\frac{I_mV_m}{I_{sc}V_{oc}}
```