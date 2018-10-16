#### Lynnesbicoin - A memecoin, built off of Turtlecoin

##### Building

- `git clone https://github.com/Frinkel/lynnesbicoin`
- `cd lynnesbicoin`
- `mkdir build && cd $_`
- `cmake ..`
- `make`


#### Linux

##### Prerequisites

- You will need the following packages: boost (1.55 or higher), rocksdb, cmake, git, gcc (4.9 or higher), g++ (4.9 or higher), make, and python. Most of these should already be installed on your system.
- For example on Ubuntu: `sudo apt-get install -y build-essential python-dev gcc g++ git cmake libboost-all-dev`

##### Building

- `git clone https://github.com/Frinkel/lynnesbicoin`
- `cd lynnesbicoin`
- `mkdir build && cd $_`
- `cmake ..`
- `make`

#### Apple

##### Prerequisites

- Install [cmake](https://cmake.org/). See [here](https://stackoverflow.com/questions/23849962/cmake-installer-for-mac-fails-to-create-usr-bin-symlinks) if you are unable call `cmake` from the terminal after installing.
- Install the [boost](http://www.boost.org/) libraries. Either compile boost manually or run `brew install boost`.
- Install XCode and Developer Tools.

##### Building

- `git clone -b master https://github.com/Frinkel/lynnesbicoin`
- `cd lynnesbicoin`
- `mkdir build && cd $_`
- `cmake ..` or `cmake -DBOOST_ROOT=<path_to_boost_install> ..` when building
  from a specific boost install. If you used brew to install boost, your path is most likely `/usr/local/include/boost.`
- `make`

The binaries will be in `./src` after compilation is complete.

Run `./src/Lynnesbicoind` to connect to the network and let it sync (it may take a while).

#### Windows 10

- Uhhhh tbh not sure 100% if it can be built in windows yet, plz use linux
- You might just be able to use the directions for TurtleCoin, just replace all instances of Turtlecoin with Lynnesbiancoin

#### Thank You
Cryptonote Developers, Bytecoin Developers, Monero Developers, Forknote Project, TurtleCoin Community
Especially thank you to the TurtleCoin community/devs for creating (from what I've seen) the only halfway decent altcoin fork tutorial.
