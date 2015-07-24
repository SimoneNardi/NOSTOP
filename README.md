# nostop

API index
This repository is a container for all (or most of the) packages needed for the nostop project. To download everything at once, simply use the command
git clone --recursive https://github.com/SimoneNardi/nostop.git
or, if you already set-up an ssh-key for you account
git clone --recursive git@github.com:SimoneNardi/nostop.git

When you clone this repo you will have all the submodules fixed at a certain version (that can be updated just committing on this repo when you update the submodule).
To have the last version of each submodule you should run:
git submodule foreach git checkout master
to switch from the fixed version and then:
git submodule foreach git pull
