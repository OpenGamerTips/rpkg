# rpkg - The all-in-one package manager.
(retarded thing i made when learning linux. it doesn't install dependencies so it's basically useless)
Rpkg is an all-in-one package manager that is for Arch-Based Linux Distros. This package manager can successfuly install *.deb* packages and fully support it.

### Installation

Grab the file from this repository. While your file manager is open as root, drag and drop [rpkg](rpkg) into ***/bin/***. After that, open the terminal and paste this in:
```
cd /bin/
sudo chmod +x rpkg
```

After that, you should be able to use the rpkg command. Before we do that, you have to install some dependencies. Add this to your terminal:
```
sudo pacman -Syu
sudo pacman -S p7zip
sudo pacman -S snap
```

Rpkg is completely installed. Type 'rpkg -h' to see the list of commands.
