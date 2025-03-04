# Raspberry Pi Cluster
Weekend class project to create a 4 node cluster from raspberry pi model 4B 2GB RAM and a gigabit ethernet switch<br>
## Projects used:<br>
https://github.com/pmodels/mpich<br>
https://github.com/xianyi/OpenBLAS<br>
https://www.netlib.org/benchmark/hpl/<br>
Website to generate HPL.dat file: https://www.advancedclustering.com/act_kb/tune-hpl-dat-file/<br>
## Benchmark<br>
| Nodes | N | Time (seconds) | Gflops |
| - | - | - | - |
| 1 | 9984  | 46.98 | 14.127 |
| 2 | 14592 | 80.07 | 25.874 |
| 3 | 17664 | 245.62 | 14.961 |
| 4 | 20352 | 255.00 | 22.042 |
