```
sudo apt-get install gcc-X
sudo apt-get install g++-X
sudo update-laternatives --install /usr/bin/gcc gcc /usr/bin/gcc-X X
sudo update-laternatives --install /usr/bin/gcc gcc /usr/bin/gcc-Y Y

sudo update-laternatives --install /usr/bin/g++ g++ /usr/bin/g++-X X
sudo update-laternatives --install /usr/bin/g++ g++ /usr/bin/g++-Y Y

sudo update-alternatives --config gcc
```