# PnVRocqLib

A Coq library written by members of PnV Discord Server.

Currently, this library is standalone.

## Quick Start

```
git clone https://github.com/PnVDiscord/PnVRocqLib.git
cd PnVRocqLib
eval `opam env`
coq_makefile -f _CoqProject -o Makefile
make -j4 -k
```

### coqc -v

```
The Coq Proof Assistant, version 8.18.0
```

## Contents

### Data

- `Aczel.v` : Aczel's Type Theoretic Interpretation of Set Theory.

- `Vector.v` : Replaces `Coq.Vectors.VectorDef.t`.

### Index

- `Index.v` : Accumulates all source files and check their consistency.

### Math

- `BooleanAlgebra.v` : Basic Theory on Boolean Algebras.

- `ClassicalDomainTheory.v` : Classical Domain Theory.

- `DomainTheory.v` : Constructive Domain Theory.

- `OrderTheory.v` : Basic Order Theory.

- `ThN.v` : Basic facts on the natural numbers.

### Prelude

- `Classical.v` : Facts about classical logic.

- `ConstructiveFacts.v` : Facts on CIC.

- `Notations.v` : Reserves all notations to avoid the conflict.

- `SfLib.v` : The copy of `snu-sf/sflib.v`. See `References`.

- `Prelude.v` : The prelude code.

## References

1. [sflib](https://github.com/snu-sf/sflib)

2. [stdpp](https://plv.mpi-sws.org/coqdoc/stdpp)

3. [A note written by Jayadev Misra](https://www.cs.utexas.edu/users/misra/Notes.dir/KnasterTarski.pdf)

4. [Constructive Completeness Proofs and Delimited Control](https://theses.hal.science/pastel-00530424/)
