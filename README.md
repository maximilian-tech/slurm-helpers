# slurm-helpers
This repo contains some helper scripts I found helpful when using SLURM

## sallocfromsbatch
This script spawns an interactive salloc session from resources defined in an sbatch script

`sallocfromsbatch <my_sbatch_script.sbatch>`

## ssbatch
This script uses an existing job for spawning an srun on that resource, if avaibale, otherwise uses `sallocfromsbatch` to spawn a session in background and use that.

`ssbatch <my_sbatch_script.sbatch>`



# Contribution
Feel free to contribute!
