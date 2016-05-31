#  vim
sudo apt-get install python3-pip
pip install pyflakes pep8 pylint ipython

git clone https://github.com/igxmill/vim.git /Downloads/dotfiles/
cp -r /Downloads/dotfiles/.vim/ ~/.vim/
mv /Downloads/dotfiles/vim/.vimrc ~/

rm -rf ~/.vim/bundle/Vundle.vim
git clone https://github.com/gmarik/Vundle.vim.git ~/.vim/bundle/Vundle.vim

Run VIM and enter:
:PluginInstall

Colorscheme:
https://github.com/morhetz/gruvbox
