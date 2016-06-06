# .bash_from_git
Provides a central place to store my git aliases, stuff in my .bashrc, that I want to use across different machines.

# Usage
Pull down the repo
```
$ cd ~
$ git clone https://github.com/phowden/.bash_from_git.git
```
Add the following lines to your .bashrc/.bash_profile/etc
```
cwd=$(pwd)
cd ~/.bash_from_git
git pull -q origin master
source *
cd $cwd
```
