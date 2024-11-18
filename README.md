# Extended CTG Generalization and Dynamic Adjustment of Generalization Strategies in IC3

## Compilation

Refer to ./rIC3/README.md for compilation instructions.

## Execution Commands

rIC3-Standard

`cargo r --release -- -e ic3 <aig file>`

rIC3-CTG

`cargo r --release -- -e ic3 --ic3-ctg --ic3-ctg-max 3 <aig file>`

rIC3-EXCTG

`cargo r --release -- -e ic3 --ic3-ctg --ic3-ctg-max 3 --ic3-ctg-limit 5 <aig file>`

rIC3-DynAMic

`cargo r --release -- -e ic3 --ic3-ctg --ic3-dynamic <aig file>`
