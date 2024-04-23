Install OpenMp - sudo apt-get install libomp-dev / sudo apt-get install openmp
Run Code :
    g++ -fopenmp filename.cpp -o filename
    ./filename
Cuda Code Run :
    nvcc filename.cu -o filename
    ./filename
