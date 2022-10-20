# VMD init files and plugins

This repo contains the .vmdrc and the plugins used by me for VMD. Making a 
symbolic link to the .vmdrc present here in the home directory should be enough
to use this .vmdrc and the plugins contained here.

The following commands should be enough to use the files present here for your
own VMD installation:
```bash
git clone git@github.com:rashidrafeek/VMD_Init_Files.git
cd VMD_Init_Files
git submodule init
git submodule update
ln -s $(realpath .vmdrc) ~
```
