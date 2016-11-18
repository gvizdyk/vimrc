# Install instructions

```
cd $HOME
```
### get source
```
git clone https://github.com/gvizdyk/vimrc.git
```
or
```
git clone git@github.com:gvizdyk/vimrc.git
```
### apply configuration
```
ln -s vimrc/.vimrc .vimrc
ln -s  vimrc/.vim .vim
```
### fetch plugins
```
cd vimrc
git submodule update --init
```
### install powerline fonts
```
cd .vim/powerline-fonts/
./install.sh
```
