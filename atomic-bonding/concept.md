# Atomic Bonding and Crystal Structures

This file contains core concepts for atomic bonding and bonding-related crystal structures.

For discussion-style examples, see:

➡️ [Atomic Bonding Examples](./examples.md)

---

## 1. General Bonding Principles

A bond forms when the bonded state has lower energy than the separated atoms.

```math
E_{\text{bonded}}<E_{\text{separate atoms}}
```

This means bonding is energetically favourable when it makes the system more stable.

In atoms, the outer-shell electrons are called valence electrons.

Valence electrons control how atoms bond because they can be:

- transferred
- shared
- delocalised
- involved in weak dipole interactions

The general relationship is:

```math
\text{valence electrons}
\rightarrow
\text{bonding type}
\rightarrow
\text{crystal structure}
\rightarrow
\text{electronic behaviour}
```

---

## 2. Interatomic Forces

When two atoms approach each other, both attractive and repulsive forces act between them.

---

### 2.1 Attractive Force

At relatively large separation, attractive force dominates.

The attraction is mainly electrostatic attraction between:

```math
\text{negative electrons}
```

and:

```math
\text{positive neighbouring nucleus}
```

This attractive force pulls atoms together and lowers the potential energy.

---

### 2.2 Repulsive Force

At very small separation, repulsive force dominates.

Repulsion occurs because:

- electron clouds overlap
- electrons repel other electrons
- nuclei repel other nuclei
- Pauli exclusion prevents electrons from occupying the same quantum state

This repulsive force prevents atoms from collapsing into each other.

---

### 2.3 Net Force

The net force is the sum of attractive and repulsive forces.

```math
F_N=F_A+F_R
```

where:

- `F_N` = net force
- `F_A` = attractive force
- `F_R` = repulsive force

At equilibrium:

```math
F_N=0
```

At this point, attraction and repulsion balance.

---

## 3. Bond Length and Bond Energy

### 3.1 Bond Length

The equilibrium interatomic separation is called the bond length.

```math
r_0=\text{bond length}
```

At this separation:

```math
F_N=0
```

and the potential energy is minimum.

---

### 3.2 Bond Energy

Bond energy is the energy required to separate bonded atoms back to infinite separation.

```math
E_0=\text{energy required to break the bond}
```

A deeper potential energy well means a stronger bond.

```math
E_0 \uparrow
\Rightarrow
\text{stronger bond}
```

A shallower potential energy well means a weaker bond.

```math
E_0 \downarrow
\Rightarrow
\text{weaker bond}
```

Strong bonds usually give:

- high melting temperature
- high stiffness
- high strength

Weak bonds usually give:

- low melting temperature
- low stiffness
- easier deformation

---

## 4. Interatomic Force and Potential Energy Curve

![Interatomic force and potential energy curve](../images/net_force.png)

The left-hand graph shows net force as a function of interatomic separation.

The right-hand graph shows potential energy as a function of interatomic separation.

---

### 4.1 Force Curve

At large separation:

```math
r\rightarrow\infty
```

the interaction between atoms is weak.

As atoms approach each other, attractive force increases.

```math
\text{electron-nucleus attraction}
\rightarrow
\text{atoms pull together}
```

When the atoms become too close, electron shells overlap and repulsive force increases rapidly.

```math
\text{small }r
\rightarrow
\text{strong repulsion}
```

At the equilibrium separation:

```math
r=r_0
```

the attractive and repulsive forces balance.

```math
F_N=0
```

Therefore:

```math
r_0=\text{equilibrium separation}=\text{bond length}
```

---

### 4.2 Potential Energy Curve

When atoms are infinitely far apart, their interaction is usually defined as zero.

```math
r\rightarrow\infty
```

```math
U=0
```

As atoms move closer, attractive interaction lowers the potential energy.

```math
\text{attraction}
\rightarrow
U\text{ decreases}
```

When atoms become too close, repulsion dominates and the potential energy rises sharply.

```math
\text{strong repulsion}
\rightarrow
U\text{ increases sharply}
```

The stable bond occurs at the minimum of the net potential energy curve.

```math
U=U_{\min}
```

This occurs at:

```math
r=r_0
```

---

### 4.3 Relationship Between Force and Energy Graphs

The two graphs describe the same equilibrium point.

| Force graph | Energy graph |
|---|---|
| `F_N = 0` | `U = U_min` |
| attractive and repulsive forces balance | potential energy is minimum |
| `r = r0` | `r = r0` |
| equilibrium separation | equilibrium separation |
| bond length | bond length |

The bond energy is labelled as:

```math
E_0
```

It is the energy required to separate atoms from the minimum-energy bonded state to infinite separation.

```math
E_0=U(\infty)-U(r_0)
```

Since:

```math
U(\infty)=0
```

the bond energy is the depth of the potential energy well.

---

## 5. Types of Bonding

There are two main categories of bonding:

1. primary bonding
2. secondary bonding

---

### 5.1 Primary Bonds

Primary bonds are strong bonds.

The main primary bonds are:

1. ionic bonding
2. covalent bonding
3. metallic bonding

Primary bonds strongly affect:

- bond energy
- melting temperature
- crystal structure
- mechanical properties
- electrical behaviour

---

### 5.2 Secondary Bonds

Secondary bonds are weaker bonds.

The main secondary bonds are:

1. van der Waals bonding
2. hydrogen bonding

Secondary bonds are important in:

- molecular solids
- layered materials
- polymers
- biological materials

---

# 6. Ionic Bonding

## 6.1 Basic Mechanism

Ionic bonding usually occurs between metals and non-metals.

It involves electron transfer.

```math
\text{metal atom loses electron}
```

```math
\text{non-metal atom gains electron}
```

This produces oppositely charged ions:

```math
\text{cation}+\text{anion}
```

The ionic bond is caused by electrostatic attraction between opposite charges.

```math
\text{opposite charges}
\rightarrow
\text{electrostatic attraction}
\rightarrow
\text{ionic bond}
```

---

## 6.2 Sodium Chloride Example

Sodium has one valence electron and can lose it to form a positive ion.

```math
\text{Na}\rightarrow \text{Na}^+ + e^-
```

Chlorine is missing one electron in its outer shell and can gain one electron to form a negative ion.

```math
\text{Cl}+e^- \rightarrow \text{Cl}^-
```

After electron transfer:

```math
\text{Na}^+ + \text{Cl}^- \rightarrow \text{NaCl}
```

The positive and negative ions attract until the attractive force is balanced by repulsion between closed electron shells.

---

## 6.3 Energetics of Ionic Bonding

Ionic bonding includes three energy processes.

### Ionisation Energy

Energy is required to remove an electron from the metal atom.

```math
\text{Na}\rightarrow \text{Na}^+ + e^-
```

This energy input is called ionisation energy.

---

### Electron Affinity

Energy is released when the non-metal atom gains an electron.

```math
\text{Cl}+e^- \rightarrow \text{Cl}^-
```

This released energy is related to electron affinity.

---

### Lattice Energy

When many ions arrange into a crystal, electrostatic attraction releases lattice energy.

For a stable ionic solid:

```math
\text{energy released}>\text{energy required}
```

Therefore the ionic crystal has lower potential energy than separated atoms.

```math
E_{\text{ionic crystal}}<E_{\text{separate atoms}}
```

---

## 6.4 Ionic Crystal Properties

Ionic solids usually have:

- strong electrostatic bonding
- high melting temperature
- rigid crystal structures
- brittle behaviour
- poor electrical conductivity in solid form
- poor thermal conductivity compared with metals

Poor electrical conductivity occurs because electrons are fixed in ions.

```math
\text{electrons fixed in ions}
\rightarrow
\text{no free electrons}
\rightarrow
\text{poor conductivity}
```

Brittleness occurs because shifting ion layers can place like charges next to each other.

```math
\text{like charges adjacent}
\rightarrow
\text{repulsion}
\rightarrow
\text{fracture}
```

---

# 7. Covalent Bonding

## 7.1 Basic Mechanism

Covalent bonding occurs when atoms share valence electrons.

```math
\text{covalent bonding}
=
\text{sharing valence electrons}
```

Atoms share electrons to complete their outer shells and reduce total potential energy.

---

## 7.2 Orbital Overlap

When two atoms approach, their outer electron shells overlap.

The shared electrons spend time between both nuclei.

This creates a region of negative charge between the positive nuclei.

```math
\text{shared electron density between nuclei}
\rightarrow
\text{electrostatic attraction}
\rightarrow
\text{covalent bond}
```

---

## 7.3 Hydrogen Molecule Example

Two hydrogen atoms each have one electron.

When they form a molecule, the two electrons are shared.

```math
\text{H}+\text{H}\rightarrow \text{H}_2
```

Each hydrogen atom effectively obtains a filled first shell.

---

## 7.4 Directional Bonding

Covalent bonds are directional.

This means the bonds prefer fixed angles.

For tetrahedral covalent bonding:

```math
\theta\approx109.5^\circ
```

This angle appears in structures such as methane, diamond, silicon and germanium.

---

## 7.5 Covalent Solid Properties

Covalent solids usually have:

- strong bonds
- high bond energy
- high melting temperature
- high hardness
- low malleability
- poor electrical conductivity if electrons are locked in bonds

Examples include:

- diamond
- silicon
- germanium
- silicon dioxide

Covalent bonding can produce either insulating or semiconducting behaviour depending on the band gap.

---

## 7.6 Silicon and Covalent Bonding

Silicon is a group IV element.

It has four valence electrons.

Each silicon atom forms four covalent bonds with neighbouring silicon atoms.

```math
\text{Si has 4 valence electrons}
\rightarrow
\text{4 covalent bonds}
```

This produces tetrahedral bonding.

```math
\text{tetrahedral bonding}
\rightarrow
\text{diamond cubic structure}
```

Silicon is not metallic because its valence electrons are mostly localised in covalent bonds.

However, silicon has a moderate band gap, so some electrons can be excited into the conduction band.

```math
\text{covalent bonding}
+
\text{moderate band gap}
\rightarrow
\text{semiconductor}
```

---

# 8. Metallic Bonding

## 8.1 Basic Mechanism

Metal atoms usually have only a few outer-shell electrons.

These electrons require relatively little energy to remove.

When many metal atoms come together, the outer electrons become delocalised.

They are no longer attached to one atom.

Instead, they form an electron gas or sea of electrons.

```math
\text{metal atoms}
\rightarrow
\text{positive ion cores}
+
\text{delocalised electron sea}
```

---

## 8.2 Metallic Bond Formation

The metallic bond is the electrostatic attraction between:

```math
\text{positive ion cores}
```

and:

```math
\text{delocalised electron sea}
```

The energy gained from this electrostatic attraction compensates for the initial energy required to remove the outer electrons from individual atoms.

---

## 8.3 Non-Directional Bonding

Metallic bonding is non-directional.

This means the bond does not depend strongly on fixed bond angles.

Therefore metal ions can pack closely together.

```math
\text{non-directional bonding}
\rightarrow
\text{close-packed crystal structures}
```

Common metal crystal structures include:

- BCC
- FCC
- HCP

---

## 8.4 Electrical Conductivity

Metals conduct electricity well because delocalised electrons can move through the solid.

When an electric field is applied:

```math
\text{delocalised electrons}
\rightarrow
\text{electron drift}
\rightarrow
\text{electric current}
```

Therefore:

```math
\text{metallic bonding}
\rightarrow
\text{mobile electrons}
\rightarrow
\text{high electrical conductivity}
```

---

## 8.5 Thermal Conductivity

Metals conduct heat well because free electrons can transfer energy from hot regions to cold regions.

```math
\text{mobile electrons}
\rightarrow
\text{efficient thermal energy transfer}
```

---

## 8.6 Malleability and Ductility

Metals are usually malleable and ductile.

Because metallic bonding is non-directional, positive ions can move relative to each other while remaining bonded by the electron sea.

```math
\text{ions slide}
+
\text{electron sea remains}
\rightarrow
\text{malleability and ductility}
```

---

# 9. Van der Waals Bonding

## 9.1 Basic Mechanism

Van der Waals bonding is a weak secondary bonding mechanism.

It comes from weak electrostatic attraction between dipoles.

```math
\text{dipole-dipole attraction}
\rightarrow
\text{van der Waals bonding}
```

---

## 9.2 Permanent Dipoles

A permanent dipole forms when charge is unevenly distributed in a molecule.

Example:

```math
\text{HCl}
```

Chlorine attracts electrons more strongly than hydrogen.

Therefore:

- Cl side becomes more negative
- H side becomes more positive

This creates a polar molecule.

If polar molecules are aligned appropriately, their dipoles attract.

```math
\text{polar molecules}
\rightarrow
\text{dipole attraction}
\rightarrow
\text{van der Waals bonding}
```

---

## 9.3 Hydrogen Bonding

Hydrogen bonding is a special type of dipole bonding.

It occurs when the positive side of a dipole comes from an exposed hydrogen nucleus.

Hydrogen bonding is stronger than ordinary van der Waals bonding but weaker than primary bonding.

---

## 9.4 Induced Dipoles

Van der Waals bonding can also occur between neutral atoms and non-polar molecules.

Electrons are always moving.

At one instant, the electron distribution may be slightly displaced from the nucleus.

This creates a temporary dipole.

A temporary dipole can induce a dipole in a neighbouring atom.

```math
\text{temporary dipole}
\rightarrow
\text{induced dipole}
\rightarrow
\text{weak attraction}
```

---

## 9.5 Van der Waals Solid Properties

Van der Waals forces are weak and decrease rapidly with separation.

```math
F_{\text{vdW}}\propto\frac{1}{r^4}
```

Van der Waals bonded materials often form:

- loosely packed crystals
- layered materials

They usually have:

- low melting temperature
- low elastic modulus
- poor thermal conductivity
- poor electrical conductivity
- easy deformation

---

# 10. Crystalline Solids

## 10.1 Crystalline Solid

A crystalline solid has atoms arranged in a regular repeating pattern.

```math
\text{periodic arrangement}
\rightarrow
\text{long-range order}
```

Long-range order means that atom positions can be predicted throughout the crystal.

---

## 10.2 Unit Cell

A unit cell is the smallest volume of atoms required to reproduce the whole crystal structure by repetition in three dimensions.

```math
\text{unit cell repeated in 3D}
\rightarrow
\text{whole crystal}
```

---

## 10.3 Lattice and Basis

A crystal structure can be described as:

```math
\text{lattice}+\text{basis}=\text{crystal structure}
```

### Lattice

A lattice is an infinite periodic array of geometric points.

It does not itself include atoms.

### Basis

A basis is the atom or group of atoms attached to each lattice point.

### Crystal Structure

A crystal structure is formed by placing the same basis at every lattice point.

---

## 10.4 Lattice Parameter

The lattice parameter is the length of the unit cell.

```math
a=\text{lattice parameter}
```

For cubic cells, the unit cell edges all have length `a`.

---

# 11. Cubic Crystal Structures

## 11.1 Simple Cubic / SC

Simple cubic is the simplest cubic crystal structure.

---

### Arrangement

Atoms are placed only at the 8 corners of a cube.

```text
corner atoms only
```

Each corner atom is shared by 8 neighbouring unit cells.

Therefore each corner contributes:

```math
\frac{1}{8}
```

Total atoms per unit cell:

```math
8\times\frac{1}{8}=1
```

So:

```math
\text{atoms per SC unit cell}=1
```

---

### Lattice Description

Simple cubic has:

- 1-atom basis
- 1 lattice point at `(0,0,0)`

The primitive translation vectors are:

```math
\mathbf{a}_1=a\hat{x}
```

```math
\mathbf{a}_2=a\hat{y}
```

```math
\mathbf{a}_3=a\hat{z}
```

---

### Coordination Number

Each atom has 6 nearest neighbours.

```math
\text{coordination number}=6
```

The nearest neighbours are along:

- `+x`
- `-x`
- `+y`
- `-y`
- `+z`
- `-z`

---

### Summary

| Feature | SC |
|---|---:|
| Unit cell shape | cube |
| Atom positions | corners only |
| Atoms per unit cell | 1 |
| Coordination number | 6 |
| Packing efficiency | low |
| Common material | rare, e.g. Po |

---

## 11.2 Body-Centred Cubic / BCC

BCC stands for body-centred cubic.

---

### Arrangement

Atoms are placed at:

1. the 8 cube corners
2. one atom at the centre of the cube body

```text
corner atoms + body-centre atom
```

Corner contribution:

```math
8\times\frac{1}{8}=1
```

Body-centre contribution:

```math
1
```

Total atoms per unit cell:

```math
1+1=2
```

So:

```math
\text{atoms per BCC unit cell}=2
```

---

### Lattice Description

BCC has:

- 1-atom basis
- 2 lattice points

The lattice points are:

```math
(0,0,0)
```

and:

```math
\left(\frac{1}{2},\frac{1}{2},\frac{1}{2}\right)
```

---

### Coordination Number

Each atom has 8 nearest neighbours.

```math
\text{coordination number}=8
```

The centre atom is surrounded by 8 corner atoms.

---

### Typical Materials

Examples:

- Fe
- W
- Cr

---

### Summary

| Feature | BCC |
|---|---:|
| Unit cell shape | cube |
| Atom positions | corners + body centre |
| Lattice points | `(0,0,0)`, `(1/2,1/2,1/2)` |
| Atoms per unit cell | 2 |
| Coordination number | 8 |
| Common materials | Fe, W, Cr |

---

## 11.3 Face-Centred Cubic / FCC

FCC stands for face-centred cubic.

---

### Arrangement

Atoms are placed at:

1. the 8 cube corners
2. the centre of each of the 6 cube faces

```text
corner atoms + face-centred atoms
```

Corner contribution:

```math
8\times\frac{1}{8}=1
```

Each face-centred atom is shared by 2 unit cells.

So each face atom contributes:

```math
\frac{1}{2}
```

Face contribution:

```math
6\times\frac{1}{2}=3
```

Total atoms per unit cell:

```math
1+3=4
```

So:

```math
\text{atoms per FCC unit cell}=4
```

---

### Lattice Description

FCC has:

- 1-atom basis
- 4 lattice points

The lattice points are:

```math
(0,0,0)
```

```math
\left(0,\frac{1}{2},\frac{1}{2}\right)
```

```math
\left(\frac{1}{2},0,\frac{1}{2}\right)
```

```math
\left(\frac{1}{2},\frac{1}{2},0\right)
```

---

### Coordination Number

Each atom has 12 nearest neighbours.

```math
\text{coordination number}=12
```

---

### Packing Factor

FCC is closely packed.

```math
\text{packing factor}=74\%
```

This means 74% of the unit cell volume is occupied by atoms.

---

### Typical Materials

Examples:

- Cu
- Al
- Ni
- Ag
- Au

---

### Summary

| Feature | FCC |
|---|---:|
| Unit cell shape | cube |
| Atom positions | corners + face centres |
| Lattice points | `(0,0,0)`, `(0,1/2,1/2)`, `(1/2,0,1/2)`, `(1/2,1/2,0)` |
| Atoms per unit cell | 4 |
| Coordination number | 12 |
| Packing factor | 74% |
| Common materials | Cu, Al, Ni, Ag, Au |

---

## 11.4 Why Metals Commonly Form BCC, FCC or HCP

Metals have metallic bonding.

Metallic bonding is non-directional.

Therefore metal ions do not need to sit at fixed bond angles.

Instead, positive ion cores can pack closely inside the delocalised electron sea.

```math
\text{metallic bonding}
\rightarrow
\text{non-directional}
\rightarrow
\text{close packing}
```

This is why metals commonly form:

- BCC
- FCC
- HCP

FCC and HCP have the highest packing factor.

```math
\text{FCC packing factor}=\text{HCP packing factor}=74\%
```

---

# 12. Hexagonal Close-Packed / HCP

## 12.1 Basic Arrangement

HCP stands for hexagonal close-packed.

HCP consists of close-packed atomic layers.

The stacking sequence is:

```math
ABABAB\cdots
```

This means:

- first layer = `A`
- second layer = `B`
- third layer = directly above `A`
- fourth layer = directly above `B`

So the layers alternate:

```text
A layer
B layer
A layer
B layer
...
```

---

## 12.2 Conventional Hexagonal Cell

The conventional hexagonal cell contains atoms at:

- the corners of the top and bottom hexagons
- the centres of the top and bottom faces
- three atoms in the middle layer

The conventional hexagonal cell contains 6 atoms in total.

```math
\text{atoms per conventional HCP cell}=6
```

---

## 12.3 Primitive Cell

The primitive rhombohedral unit cell contains 2 atoms.

The lattice points are:

```math
(0,0,0)
```

and:

```math
\left(\frac{2}{3},\frac{1}{3},\frac{1}{2}\right)
```

---

## 12.4 Coordination Number and Packing

Each atom has 12 nearest neighbours.

```math
\text{coordination number}=12
```

HCP has the same packing factor as FCC.

```math
\text{packing factor}=74\%
```

---

## 12.5 Typical Materials

Examples:

- Mg
- Ti
- Zn
- Co

---

## 12.6 Summary

| Feature | HCP |
|---|---:|
| Unit cell type | hexagonal / rhombohedral primitive cell |
| Layer stacking | ABAB |
| Atoms per conventional hexagonal cell | 6 |
| Atoms per primitive cell | 2 |
| Coordination number | 12 |
| Packing factor | 74% |
| Common materials | Mg, Ti, Zn, Co |

---

# 13. Diamond Cubic Structure

## 13.1 Basic Arrangement

Diamond cubic is common in covalent solids such as:

- diamond
- silicon
- germanium

Diamond cubic can be described as an FCC lattice with a two-atom basis.

```math
\text{diamond cubic}
=
\text{FCC lattice}
+
\text{two identical atom basis}
```

---

## 13.2 FCC Lattice Points

The FCC lattice points are:

```math
(0,0,0)
```

```math
\left(0,\frac{1}{2},\frac{1}{2}\right)
```

```math
\left(\frac{1}{2},0,\frac{1}{2}\right)
```

```math
\left(\frac{1}{2},\frac{1}{2},0\right)
```

---

## 13.3 Two-Atom Basis

The two identical atoms in the basis are placed at:

```math
(0,0,0)
```

and:

```math
\left(\frac{1}{4},\frac{1}{4},\frac{1}{4}\right)
```

Because the FCC lattice has 4 lattice points per conventional unit cell and the basis has 2 atoms:

```math
4\times2=8
```

So:

```math
\text{atoms per diamond cubic unit cell}=8
```

---

## 13.4 Bonding Arrangement

Each atom forms covalent bonds with 4 nearest neighbours.

```math
\text{coordination number}=4
```

The bonds form a tetrahedral arrangement.

```math
\text{bond angle}\approx109.5^\circ
```

This is why diamond cubic is less closely packed than FCC or HCP.

---

## 13.5 Silicon Example

Silicon has four valence electrons.

Each silicon atom forms four covalent bonds.

```math
\text{Si has 4 valence electrons}
\rightarrow
\text{4 covalent bonds}
\rightarrow
\text{diamond cubic}
```

---

## 13.6 Summary

| Feature | Diamond cubic |
|---|---:|
| Lattice type | FCC |
| Basis | two identical atoms |
| Basis positions | `(0,0,0)`, `(1/4,1/4,1/4)` |
| Atoms per conventional unit cell | 8 |
| Coordination number | 4 |
| Bonding | tetrahedral covalent |
| Common materials | diamond, Si, Ge |

---

# 14. Zincblende Structure

## 14.1 Basic Arrangement

Zincblende is common in compound semiconductors such as:

- GaAs
- InP
- ZnS

Zincblende is similar to diamond cubic, but the two atoms in the basis are different.

```math
\text{diamond cubic}
=
\text{two identical atoms in basis}
```

```math
\text{zincblende}
=
\text{two different atoms in basis}
```

---

## 14.2 GaAs Example

For GaAs, the two-atom basis can be written as:

```math
\text{As at }(0,0,0)
```

```math
\text{Ga at }\left(\frac{1}{4},\frac{1}{4},\frac{1}{4}\right)
```

The structure can be viewed as two interpenetrating FCC sublattices:

- one sublattice for As
- one shifted sublattice for Ga

---

## 14.3 Bonding Arrangement

Each atom is tetrahedrally bonded to 4 atoms of the opposite type.

For GaAs:

```math
\text{each Ga atom bonds to 4 As atoms}
```

```math
\text{each As atom bonds to 4 Ga atoms}
```

The bonding has covalent character and may also have partial ionic character because the two atoms are different.

---

## 14.4 Summary

| Feature | Zincblende |
|---|---:|
| Lattice type | FCC-like |
| Basis | two different atoms |
| Example basis | As at `(0,0,0)`, Ga at `(1/4,1/4,1/4)` |
| Coordination number | 4 |
| Bonding | tetrahedral, partly covalent / partly ionic |
| Common materials | GaAs, InP, ZnS |

---

# 15. Rock Salt Structure

## 15.1 Basic Arrangement

Rock salt is a common ionic crystal structure.

The key example is:

```math
\text{NaCl}
```

NaCl consists of alternating positive and negative ions.

```math
\text{Na}^+
```

and:

```math
\text{Cl}^-
```

sit alternately throughout the crystal.

---

## 15.2 Lattice and Basis

Rock salt can be described as an FCC structure with a two-ion basis.

A common basis description is:

```math
\text{Cl}^- \text{ at }(0,0,0)
```

```math
\text{Na}^+ \text{ at }\left(\frac{1}{2},\frac{1}{2},\frac{1}{2}\right)
```

---

## 15.3 Coordination Number

Each ion is surrounded by 6 nearest neighbours of opposite charge.

For example:

```math
\text{each Na}^+
\text{ has 6 nearest Cl}^-
```

and:

```math
\text{each Cl}^-
\text{ has 6 nearest Na}^+
```

So:

```math
\text{coordination number}=6
```

---

## 15.4 Why Rock Salt Forms

Ionic crystals arrange to maximise attraction between opposite charges and minimise repulsion between like charges.

```math
\text{maximise cation-anion attraction}
```

```math
\text{minimise cation-cation and anion-anion repulsion}
```

This produces a stable alternating ionic lattice.

---

## 15.5 Summary

| Feature | Rock salt / NaCl |
|---|---:|
| Bonding | ionic |
| Arrangement | alternating cations and anions |
| Description | FCC with two-ion basis |
| Example basis | Cl at `(0,0,0)`, Na at `(1/2,1/2,1/2)` |
| Coordination number | 6 |
| Common materials | NaCl, MgO |

---

# 16. Structure Comparison

| Structure | Main material type | Arrangement | Atoms per unit cell | Coordination number | Main reason |
|---|---|---|---:|---:|---|
| SC | rare metal | corners only | 1 | 6 | simple but inefficient packing |
| BCC | metals | corners + body centre | 2 | 8 | metallic bonding, relatively close packing |
| FCC | metals | corners + face centres | 4 | 12 | close-packed metallic structure |
| HCP | metals | ABAB close-packed layers | 6 conventional / 2 primitive | 12 | close-packed metallic structure |
| Diamond cubic | covalent semiconductors | FCC + two identical atom basis | 8 | 4 | tetrahedral covalent bonding |
| Zincblende | compound semiconductors | diamond-like, two different atoms | 8 conventional | 4 | tetrahedral compound bonding |
| Rock salt | ionic solids | alternating cations and anions | depends on cell description | 6 | maximise opposite-charge attraction |

---

# 17. Bonding, Crystal Structure and Thermal Properties

Metals often conduct heat well because:

- atoms are closely packed
- free electrons transfer thermal energy efficiently

Covalent solids and molecular solids conduct heat less efficiently because:

- directional bonding reduces close packing
- electrons are not free
- vibrations transfer energy less effectively

The general link is:

```math
\text{crystal structure}
\rightarrow
\text{thermal properties}
```

---

# 18. Bonding, Band Structure and Electrical Behaviour

## 18.1 Metals

Bonding:

```math
\text{metallic bonding}
\rightarrow
\text{delocalised electrons}
```

Crystal structure:

```math
\text{BCC / FCC / HCP}
```

Band structure:

```math
\text{partially filled band}
```

or:

```math
\text{overlapping valence and conduction bands}
```

Electrical behaviour:

```math
\text{many mobile electrons}
\rightarrow
\text{high conductivity}
```

---

## 18.2 Insulators

Bonding:

```math
\text{ionic bonding or strong covalent bonding}
\rightarrow
\text{localised electrons}
```

Crystal structure:

```math
\text{ionic crystals or covalent networks}
```

Band structure:

```math
\text{full valence band}
```

```math
\text{empty conduction band}
```

```math
\text{large band gap}
```

Electrical behaviour:

```math
\text{few mobile carriers}
\rightarrow
\text{poor conductivity}
```

---

## 18.3 Semiconductors

Bonding:

```math
\text{covalent bonding}
```

Crystal structure:

```math
\text{diamond cubic or zincblende}
```

Band structure:

```math
\text{full valence band at }0\text{ K}
```

```math
\text{empty conduction band at }0\text{ K}
```

```math
\text{moderate band gap}
```

Electrical behaviour:

```math
\text{thermally generated electron-hole pairs}
\rightarrow
\text{controllable conductivity}
```

---

# 19. Summary

## 19.1 Bonding Summary

```math
\text{electron transfer}
\rightarrow
\text{ionic bonding}
```

```math
\text{electron sharing}
\rightarrow
\text{covalent bonding}
```

```math
\text{electron delocalisation}
\rightarrow
\text{metallic bonding}
```

```math
\text{dipole attraction}
\rightarrow
\text{van der Waals bonding}
```

---

## 19.2 Structure Summary

```math
\text{metallic bonding}
\rightarrow
\text{BCC / FCC / HCP}
```

```math
\text{ionic bonding}
\rightarrow
\text{rock salt and other ionic crystals}
```

```math
\text{covalent bonding}
\rightarrow
\text{diamond cubic / zincblende}
```

```math
\text{van der Waals bonding}
\rightarrow
\text{loosely packed or layered solids}
```

---

## 19.3 Electrical Behaviour Summary

```math
\text{mobile electrons}
\rightarrow
\text{conductor}
```

```math
\text{localised electrons + large band gap}
\rightarrow
\text{insulator}
```

```math
\text{localised covalent electrons + moderate band gap}
\rightarrow
\text{semiconductor}
```