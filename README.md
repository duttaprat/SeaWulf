# SeaWulf
Simple guide to use the SeaWulf server


## Important links
* https://it.stonybrook.edu/help/kb/seawulf-queues
* https://it.stonybrook.edu/help/kb/using-the-slurm-workload-manager


## Accessing the GPU
1. module load slurm 
2. srun -N 1 -n 28 -t 8:00:00 -p gpu --pty bash
