# my_cuda_playground
multipy 2X2  matirx using cuda for ecucation purpose
##  install dependency
```bash
wget https://developer.download.nvidia.com/compute/cuda/11.4.1/local_installers/cuda_11.4.1_470.57.02_linux.run
sudo sh cuda_11.4.1_470.57.02_linux.run
```


## compile and run
```bash
$ make &&./matrixMul
[Matrix Multiply Using CUDA] - Starting...
GPU Device 0: "Maxwell" with compute capability 5.0

MatrixA(2,2), MatrixB(2,2)
0.100000 0.200000 0.300000 0.400000 
0.500000 0.600000 0.700000 0.800000 
Computing result using CUDA Kernel...
MatrixC(2,2)
0.190000 0.220000 0.430000 0.500000 
$
```
