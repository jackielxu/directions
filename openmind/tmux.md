#  How to download tmux onto Openmind

1. Download [linuxbrew](http://linuxbrew.sh/) and add the following to your .bashrc
```
export PATH="$HOME/.linuxbrew/bin:$PATH"
export MANPATH="$HOME/.linuxbrew/share/man:$MANPATH"
export INFOPATH="$HOME/.linuxbrew/share/info:$INFOPATH"
```

2. If you are missing makeinfo, download the latest version of [texinfo](https://www.gnu.org/software/texinfo/). 
  * Download the .tar.gz file with wget, and open with ```tar -zxvf texinfo-6.1.tar.gz ```
  * Open the texinfo directory and compile by following the instructions [here](http://www.linuxfromscratch.org/lfs/view/stable/chapter05/texinfo.html)

3. Gave up (for now) ... using screen.
