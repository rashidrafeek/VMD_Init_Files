# VMD init files and plugins

This repo contains the .vmdrc and the plugins used by me for VMD. To use the
the files present here for your own VMD installation, create a symbolic link 
to the .vmdrc present here in the home directory, after cloning the repo and
submodules. The following commands can be used for this:
```bash
git clone git@github.com:rashidrafeek/VMD_Init_Files.git
cd VMD_Init_Files
git submodule init
git submodule update
ln -s $(realpath .vmdrc) ~
```
