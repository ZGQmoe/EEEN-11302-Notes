# Atomic Structure — Examples

Back to concepts:

⬅️ [Atomic Structure Concepts](./concept.md)

---

## 1. Bound Electron: PE, KE and Sign Convention

**Use when:** a question gives total energy and asks for potential/kinetic energy.

Related concepts:

- [Coulomb Potential Energy](./concept.md#5-coulomb-potential-energy)
- [Bound Electron Energy](./concept.md#6-bound-electron-energy)

---

### Key Idea

For an electron bound to a positive nucleus:

```math
PE<0
```

Kinetic energy must be positive:

```math
KE>0
```

For a Coulomb-bound electron:

```math
KE=\frac{1}{2}|PE|
```

Since $begin:math:text$PE\<0$end:math:text$:

```math
KE=-\frac{1}{2}PE
```

---

### Method

Start with:

```math
E_{\text{total}}=KE+PE
```

Substitute:

```math
KE=-\frac{1}{2}PE
```

Then:

```math
E_{\text{total}}
=
-\frac{1}{2}PE+PE
```

```math
E_{\text{total}}
=
\frac{1}{2}PE
```

So:

```math
PE=2E_{\text{total}}
```

Then:

```math
KE=E_{\text{total}}-PE
```

or:

```math
KE=-\frac{1}{2}PE
```

---

### Common Mistake

Do not write:

```math
KE=\frac{1}{2}PE
```

because $begin:math:text$PE$end:math:text$ is negative and $begin:math:text$KE$end:math:text$ cannot be negative.

Correct form:

```math
KE=\frac{1}{2}|PE|
```

or:

```math
KE=-\frac{1}{2}PE
```

---

## 2. Bohr Radius from Potential Energy

**Use when:** a question asks for orbital radius from Coulomb potential energy.

Related concept:

- [Bohr Radius](./concept.md#7-bohr-radius)

---

### Key Formula

For an electron bound to a positive nucleus:

```math
PE=-\frac{k_e e^2}{r_0}
```

Rearrange:

```math
r_0=\frac{k_e e^2}{|PE|}
```

---

### Method

1. Find $begin:math:text$PE$end:math:text$.
2. Use its magnitude $begin:math:text$\|PE\|$end:math:text$.
3. Substitute into:

```math
r_0=\frac{k_e e^2}{|PE|}
```

---

### Common Mistake

Do not substitute a negative value directly into the denominator without thinking about the sign.

Use:

```math
|PE|
```

because radius must be positive.

---

## 3. Ionisation Energy from Photon Wavelength

**Use when:** a question gives light wavelength and treats it as ionisation threshold.

Related concepts:

- [Energy Levels from Ionisation Energy](./concept.md#83-energy-levels-from-ionisation-energy)
- [Photon Energy and Ionisation](./concept.md#84-photon-energy-and-ionisation)

---

### Key Formula

Photon energy:

```math
E=\frac{hc}{\lambda}
```

Useful shortcut:

```math
E(\text{eV})=\frac{1240}{\lambda(\text{nm})}
```

If the photon is exactly at the ionisation threshold:

```math
E_{\text{photon}}=E_{\text{ionisation}}
```

Then:

```math
E_1=-E_{\text{ionisation}}
```

---

### Method

1. Calculate photon energy:

```math
E_{\text{photon}}=\frac{1240}{\lambda(\text{nm})}
```

2. If treated as threshold:

```math
E_{\text{ionisation}}=E_{\text{photon}}
```

3. Ground-state energy:

```math
E_1=-E_{\text{ionisation}}
```

---

### Important Note

If the atom is real hydrogen with $begin:math:text$Z\=1$end:math:text$, the ionisation energy is:

```math
13.6\ \text{eV}
```

If the photon energy is larger than this, the extra energy becomes kinetic energy:

```math
K=E_{\text{photon}}-E_{\text{ionisation}}
```

---

## 4. Energy Levels from Ionisation Energy

**Use when:** a question gives or implies a ground-state ionisation energy.

Related concept:

- [Energy Levels](./concept.md#8-energy-levels)

---

### Key Formula

If ionisation energy is known:

```math
E_1=-E_{\text{ionisation}}
```

Bohr-style scaling:

```math
E_n=-\frac{E_{\text{ionisation}}}{n^2}
```

---

### Method

1. Identify $begin:math:text$E\_\{\\text\{ionisation\}\}$end:math:text$.
2. Set:

```math
E_1=-E_{\text{ionisation}}
```

3. Use:

```math
E_n=-\frac{E_{\text{ionisation}}}{n^2}
```

4. Draw levels with $begin:math:text$E\=0$end:math:text$ at the top.

---

### Diagram Pattern

```text
E = 0        ─────────────  n = infinity

             ─────────────  n = 4

             ─────────────  n = 3

             ─────────────  n = 2

             ─────────────  n = 1
```

As $begin:math:text$n$end:math:text$ increases:

```math
E_n\rightarrow0
```

---

## 5. Emission from Energy-Level Transitions

**Use when:** an electron falls from a higher shell to a lower shell.

Related concept:

- [Photon Absorption and Emission](./concept.md#9-photon-absorption-and-emission)

---

### Key Formula

For emission:

```math
E_{\text{photon}}=E_{\text{initial}}-E_{\text{final}}
```

where:

```math
E_{\text{initial}}>E_{\text{final}}
```

The photon energy must be positive.

---

### Method

1. Identify the starting shell.
2. Identify possible lower shells.
3. Calculate all possible energy gaps:

```math
\Delta E=E_{\text{higher}}-E_{\text{lower}}
```

4. Each energy gap can correspond to one emitted photon.

---

### Example Pattern

If electron starts at $begin:math:text$n\=3$end:math:text$, possible transitions include:

```math
3\rightarrow2
```

```math
3\rightarrow1
```

and, if cascade occurs:

```math
2\rightarrow1
```

So possible photon energies are:

```math
E_3-E_2
```

```math
E_3-E_1
```

```math
E_2-E_1
```

---

## 6. Hydrogen Shell Confusion

**Use when:** confused why hydrogen can have $begin:math:text$n\=2\,3\,4$end:math:text$ levels.

Hydrogen has:

```math
\text{one electron}
```

but many possible energy levels:

```math
n=1,2,3,\dots
```

Ground state:

```math
\text{electron in }n=1
```

Excited state:

```math
\text{electron in higher }n
```

Ionised state:

```math
n=\infty
```

Key reminder:

> Shells are possible energy levels. They do not all need to be occupied.