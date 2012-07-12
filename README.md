#my vimrc used across windows and linux
## Install
### Linux
####1. backup your .vim and .vimrc
```
cp ~/.vimrc ~/.vim && mv ~/.vim ~/.vim_old
```
####2. git clone
```
git clone https://github.com/cooleaf/myVim.git ~/.vim
```
####3. create link to vimrc
```
ln -sfn ~/.vim/vimrc .vimrc
```
####4. install `Vundle`
```
mkdir ~/.vim/bundle
git clone https://github.com/gmarik/vundle.git ~/.vim/bundle/vundle
```
####5. install plugins with `Vundle`
Launch `vim`, run `:BundleInstall`

####6.install ctags
```
sudo apt-get install ctags
```
####7. install font for fancy powerline here i use `yahei mono for powerline` 
```
sudo cp ~/.vim/font/yahei_mono_gvim-Powerline.ttf /usr/share/fonts/truetype
```
### Windows
####1. backup your ~/.vim(if you got one)
```
 mv ~/.vim ~/.vim_old
```
####2. git clone
```
    git clone https://github.com/cooleaf/myVim.git ~/.vim
```
####3. add this to $VIMRUNTIME/_vimrc
```
    source ~/.vim/vimrc
```
####4. install `Vundle`
```
mkdir ~/.vim/bundle
git clone https://github.com/gmarik/vundle.git ~/.vim/bundle/vundle
```
to make vundle work in windows, you may take a look at [Vundle for Windows](https://github.com/gmarik/vundle/wiki/Vundle-for-Windows)

####5. install plugins with `Vundle`
Launch `vim`, run `:BundleInstall`

####6. install ctags
#####1) download ctags from http://prdownloads.sourceforge.net/ctags/ctags58.zip
#####2) unzip it to wherever you want
#####3) add ctags.exe to PATH
####7. install font for fancy powerline here i use `yahei mono for powerline`
just double click the yaheiconsolashybrid_-Powerline.ttf and click `install`
