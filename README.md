# FeC-EAM-potential

## Usage

1. [Build LAMMPS](https://docs.lammps.org/Build_package.html) with the [MANYBODY](https://docs.lammps.org/Packages_details.html#pkg-manybody) package enabled
2. Use the following LAMMPS commands in the LAMMPS input file:

```
    pair_style      eam/alloy
    pair_coeff * *  path/to/FeC.eam Fe C
```

## References
|   Ref. |   |
|:--------:|:-:|
| Proville et al., Nature Materials, **11**, 845 (2012) | **Fe-Fe interaction**  |
|   Veiga et al., Computational Materials Science, **82**, 118 (2014)   | **Fe-C interaction**  |
|  Allera et al., _submitted for publication_ (2021)  | **hybridization** of the two previous potentials  |
