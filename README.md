# Artery Scaling Law Boundary Conditions

Scaling law boundary conditions for OpenFoam 2.1.1 based off the
paper [Functional and anatomical measures for outflow boundary conditions in atherosclerotic coronary bifurcations](https://www.researchgate.net/publication/285045581_Functional_and_anatomical_measures_for_outflow_boundary_conditions_in_atherosclerotic_coronary_bifurcations)

To install all boundary conditions source the OpenFOAM 2.1.1 .bashrc and run

``` shell
    # download the github repository
    git clone https://github.com/Chr1sC0de/ArteryScalingLawsBC.git
    # change directories to the repo and allow permission to the ./Allwmake and ./Allwclean files
    chmod -R +x ArteryScalingLawsBC
    cd  ArteryScalingLawsBC
    # install the repo
    ./Allwmake
```

To clean the installation run

``` shell
    ./Allwclean
```