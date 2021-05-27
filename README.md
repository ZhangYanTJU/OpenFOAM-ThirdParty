# OpenFOAM-ThirdParty

download all tools
```
git clone --recurse-submodules https://github.com/ZhangYanTJU/OpenFOAM-ThirdParty.git
```

## study Materials
[studyMaterials.md](learning/studyMaterials.md)

## [lagrangianExtraFunctionObjects](src/functionObjects/lagrangian)
Function object library re-adapted from OpenFOAM 5, to write to disk in the old positions file format.

## [conditionalAverage](src/functionObjects/field)
OpenFOAM functionObject for postProcessing, getting the conditional averaged fields with a given scalarField

## [sampledPlaneAverage](src/functionObjects/field)

## [autoReconstructPar](caseDicts)
Use coded function in controlDict to reconstruct the mesh and fields in the run time.

## [DLBFoam](src/chemistrySolver)
An open-source dynamic load balancing model for fast reacting flow simulations in OpenFOAM.