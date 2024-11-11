# ML-RANN
Files for the ML-RANN Package in LAMMPS

This guide assumes the user has already downloaded LAMMPS. To download LAMMPS and review LAMMPS documentation, please visit https://www.lammps.org/. To use recent RANN potentials, the ML-RANN folder in lammps/src must be updated. Navigate to the lammps/src directory, and complete the following:
  1) If the ML-RANN package has already been installed, uninstall the package

  ```
  make no-ML-RANN
  ```

  2) Remove all existing RANN files in the lammps/src directory

  ```
  rm *rann*
  ```

  3) Copy the this ML-RANN to the lammps/src directory
  4) Reinstall the ML-RANN package and compile LAMMPS

  ```
  make yes-ML-RANN
  make mpi
  ```
