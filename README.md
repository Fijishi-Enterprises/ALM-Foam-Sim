turbinesFoam
============

turbinesFoam is a library for simulating wind and marine hydrokinetic turbines
in OpenFOAM using the actuator line method.

Features
--------

`fvOptions` classes for adding actuator lines and turbines constructed from
actuator lines to any compatible solver or turbulence model, e.g.,
`simpleFoam`, `pimpleFoam`, `interFoam`, etc.


Installation
------------

```bash
cd $WM_PROJECT_USER_DIR
git clone https://github.com/turbinesFoam/turbinesFoam.git
cd turbinesFoam
./Allwmake
```


Usage
-----

There are tutorials located in `turbinesFoam/tutorials`.
