# rotatingFanInRoomOFv8
rotatingFanInRoom files adjusted to work in OpenFoam v8

This is not my project and i'm very begginer on openfoam, i just have modified some files from this tutorial https://www.youtube.com/watch?v=qtN256WJ-5I ; https://develop.openfoam.com/Development/openfoam/tree/develop/tutorials/incompressible/pimpleFoam/RAS/rotatingFanInRoom , to work with openFoam v8. Working with "openfoam-org 8.20201114-1" installed on archlinux, from https://aur.archlinux.org/packages/openfoam-org/.


If you have troubles with mpi, run 
  mpirun --use-hwthread-cpus -np 4 pimpleFoam -parallel > log.pimpleFoam &
  Explanation https://stackoverflow.com/questions/48835603/unable-to-use-all-cores-with-mpirun
