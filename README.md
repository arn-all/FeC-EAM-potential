
**Companion repository for the paper:**


Allera, A., Ribeiro, F., Perez, M., & Rodney, D. (2022). *Carbon-induced strengthening of bcc iron at the atomic scale.* Physical Review Materials, 6(1), 013608. https://doi.org/10.1103/PhysRevMaterials.6.013608

## Fe-C potential

### Contents

The interatomic potential described in the publication is provided as a ![tabulated LAMMPS potential file](https://github.com/arn-all/FeC-EAM-potential/blob/main/FeC.eam) to be used in molecular dynamics/statics simulations of the Fe-C system.

### Usage

1. [Build LAMMPS](https://docs.lammps.org/Build_package.html) with the [MANYBODY](https://docs.lammps.org/Packages_details.html#pkg-manybody) package enabled
2. Use the following LAMMPS commands in the LAMMPS input file:

```
    pair_style      eam/alloy
    pair_coeff * *  path/to/FeC.eam Fe C
```

## References
|   Ref. |   |
|:--------:|:-:|
| **Fe-Fe interaction** | <div class="csl-entry">Proville, L., Rodney, D., &#38; Marinica, M. C. (2012). Quantum effect on thermally activated glide of dislocations. <i>Nature Materials</i>, <i>11</i>(10), 845–849. https://doi.org/10.1038/nmat3401</div>  |
| **Fe-C interaction** |  <div class="csl-entry">Veiga, R. G. A., Becquart, C. S., &#38; Perez, M. (2014). Comments on “atomistic modeling of an Fe system with a small concentration of C.” <i>Computational Materials Science</i>, <i>82</i>, 118–121. https://doi.org/10.1016/j.commatsci.2013.09.048</div>   |
| **Hybridization** of the two previous potentials | <div class="csl-entry">Allera, et al. (2022) <i>Physical Review Materials</i>, <i>6</i>(1), 013608. https://doi.org/10.1103/PhysRevMaterials.6.013608</div>   |
