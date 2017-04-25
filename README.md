# vim-config for:
c
php
html
javascript

## global setting
sudo rm -rf /etc/vim
sudo mkdir -p /etc/vim
sudo cp global/* /etc/vim/

## local setting
rm -rf .vim* .fzf
cp local/.vimrc local/.vimrc.local ~