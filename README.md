# Raspberry Pi Cluster
Weekend class project to create a 4 node cluster from raspberry pi model 4B 2GB RAM and a Gigabit ethernet switch<br>
<br>
![Cable](AtrociousCableManagement.JPG)
<br>
## Benchmark ##<br>
| Nodes | N | Time (seconds) | Gflops |
| - | - | - | - |
| 1 | 9984  | 46.98 | 1.4127e+01 |
| 2 | 14592 | 80.07 | 2.5874e+01 |
| 3 | 17664 | 245.62 | 1.4961e+01 |
| 4 | 20352 | 255.00 | 2.2042e+01 |
<br>
Projects used:<br>
https://github.com/pmodels/mpich<br>
https://github.com/xianyi/OpenBLAS<br>
https://www.netlib.org/benchmark/hpl/<br>
<br>
Website used to generate HPL.dat file:<br>
https://www.advancedclustering.com/act_kb/tune-hpl-dat-file/
