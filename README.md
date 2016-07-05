Usage
=====

    blockMesh
    cp -r 0_org 0
    setFields && funkySetFields -time 0
    
1) Run the pre-conditioner.

	$ preCPhaseFieldFoam

2) Run the actual phase field solver.

	$ phaseFieldFoam
