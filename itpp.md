[IT++](http://itpp.sourceforge.net/4.3.1/) is a C++ library of mathematical, signal processing and communication classes and functions. In practice, it is useful for binary operations with matrices and vectors. There are several projects written with it, including
- belief propagation
- clifford circuit simulator (mostly with Eigen)


To run itpp and Eigen, one can
- run it on hpcc (256/512 cores at UCR cluster)
- run it on cherenkov ( a 16-core ubuntu server in MSE 312)
- install it in your own machine
- run it with Docker

Typically for any serious calculation, one need to run it on hpcc or at least cherenkov. The speed is fast and everything have been installed there. But if you just want to run some small function, or test yout program locally, Docker is a nice choice. Once you have docker installed, it takes only one command to set up an environment identical to hpcc or cherenkov. See the Dockerfile and readme [here](https://hub.docker.com/repository/docker/weileizeng/itpp-full).
