```
download cuda X.X based on gpu type: https://en.wikipedia.org/wiki/CUDA , https://developer.nvidia.com/cuda-toolkit-archive
install build-essentials libxi6:i386, libxmu6:i386, libxmu-dev, libxi-dev, libgl1-mesa-dev, libgl-dev, 
```

```
./cuda_XX.run --tar mxvf
cp InstallUtils.pm /usr/lib/x86_64-linux-gnu/perl-base

init 3

export $PERL5LIB 
sudo ./cuda_X.X.run --override

init 5

rm /usr/lib/x86_64-linux-gnu/perl-base/InstallUtils.pm

~/.bashrc
export CUDA_HOME=/usr/local/cuda
export LD_LIBRARY_PATH=${CUDA_HOME}/lib64
export PATH=${CUDA_HOME}/bin:${PATH}
```
```
<<TEST>>
cd ${CUDA_HOME}/bin
./cuda-install-samples-x.x.sh ~
cd ~/Nvidi-cuda-x.x-samples
make -j8
```

