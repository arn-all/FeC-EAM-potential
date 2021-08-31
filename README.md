# FeC-EAM-potential

## Usage

1. [Build LAMMPS](https://docs.lammps.org/Build_package.html) with the [MANYBODY](https://docs.lammps.org/Packages_details.html#pkg-manybody) package enabled
2. Use the following LAMMPS commands in the LAMMPS input file:

```
    pair_style      eam/alloy
    pair_coeff * *  path/to/FeC.eam Fe C
```

## References

1. Allera et al., _in preparation_ (2021) : **hybridization** of the two following EAM potentials
2. Proville et al., Nature materials, 11 (2012) : **Fe-Fe interaction**
3. Veiga et al., M. Comput. Materials Science, 82 (2014) : **Fe-C interaction**

