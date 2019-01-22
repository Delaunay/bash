Bash Configuration
==================

# Setup

```

.bash.d                                 # this repository 
.bashrc -> .bash.d/main.env             # link to main.env
usr/$arch/{lib, bin, include, share}    # Installation of user libraries
anaconda/$arch/                         # Installation of anaconda 

```

# Installation

```

git clone ~/.bash.d
mv ~/.bash.rc bash.rc.bak
ln -s ~/.bash.d/main.env ~/.bashrc

```
