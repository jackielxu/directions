# Installing Node.js on OpenMind

1. Download the Node.js [source code](https://nodejs.org/en/download/). Run: 
  - `wget "https://nodejs.org/en/download/"`
  - `tar -xzvf [TAR_GZ_FILE_NAME]`

2. `cd` into the directory that is created, and install the package with the following commands:
  - `./configure --prefix=$HOME/myapps`
  - `make`
  - `make install`

3. Add the following line to your .bashrc file. Then, recompile the .bashrc file with `source ~/.bashrc`.
  - `export PATH="$HOME/myapps/bin:$PATH"`
