# OmegaMaxEnt

OmegaMaxEnt is a tool for the analytic continuation of Matsubara data. 
It is published under the [GNU Public License, version 3][license]. 
See the [citation page][cite] if you use the program in publications.

Original code: [dbergeron1/OmegaMaxEnt](https://github.com/dbergeron1/OmegaMaxEnt).
Latter modified by Moise Rousseau keeping the code up to date.

## Getting started

1. Install the necessary dependencies BLAS/LAPACK, FFTW3 and Armadillo.
For example, for Ubuntu system (adapt to our own machine)
```
sudo apt install cmake libarmadillo-dev libfftw3-dev
```
Or, load the following modules on Digital Research Alliance of Canada' systems (formerly ComputeCanada):
```
module load StdEnv/2020 gcc/9.3.0 fftw/3.3.8 cmake/3.23.1 armadillo/9.900.2
```

2. Clone this repository:
```
git clone https://github.com/MoiseRousseau/OmegaMaxEnt && cd OmegaMaxEnt
```

3. Build `OmegaMaxEnt`:
```
mkdir build && cd build
cmake ..
make
```

Yo are good to go.

[cite]: https://www.physique.usherbrooke.ca/MaxEnt/index.php?title=Citation
[OME_web]: https://www.physique.usherbrooke.ca/MaxEnt/index.php/Main_Page
[license]: http://www.gnu.org/licenses/gpl.html
