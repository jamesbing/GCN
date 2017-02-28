# CUDA_CNN

1. Install CUDA

2. Download GCN from https://github.com/jdjd1114/GCN
   <br>`bash`
   cd path_to_GCN/
   
3. Compile (Note that MATLAB path in Makefile may need to be modified.)
   <br>`bash`
   make
   
4. run the program
   <br>`bash`
   ./bin/gcn data/DATANAME.mat
   <bar> Dataset consists of two parts: 
   <bar> * Dataset, a 3-dimensional hyperspectal image
   <bar> * Labels, a 2-dimensional label matrix
