# Run Boltz-1 Model With Arbitrary Non-Canonical Amino Acids

A jupyter notebook which walks you through injecting a new residue into the CCD cache and then using 
that new residue as a modification in a boltz yaml file. 
All you need for the input is a smiles string representing the molecule attached to an amino acid.

Runs with any python environment that can run Boltz inference.

NOTE: to remove extra OXT atoms clone from this patch branch for now until the authors update the original repo to not leave OXT atoms.
https://github.com/jwohlwend/boltz/pull/93
