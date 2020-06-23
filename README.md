# Forcefields
LAMMPS compatible interatomic potentials

In this repository you will find a number of potentials for different materials. These potentials work with the LAMMPS simulation package using the QUIP pair style command. They can also be used in the ASE simulation environment. It is important to read the README files found in each repository for information regarding citations as well as information about the fitting of the potential as well as the tested environments.

In each directory corresponding to a material, you will find the .xml files corresponding to the potential, an example LAMMPS input file which may be used, and an example initial configuration of whichever material the potential has been fit to. If you have any question or problems, please feel free to contact Samuel Tovey at:
```
tovey.samuel@gmail.com
```
or alternatively,
```
stovey@icp.uni-stuttgart.de
```

What follows is a quick summary of the families of materials which are found in this repository.
## Molten Salts
In this directory all of the forcefields for the molten salts will be added. Check the README in this directory for more information about using the potentials


## Important Notes

* LAMMPS will only function with the metal units when using ML potentials
