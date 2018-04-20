#install [pathogen](https://github.com/tpope/vim-pathogen)

mkdir -p ~/.vim/autoload ~/.vim/bundle && \
curl -LSso ~/.vim/autoload/pathogen.vim https://tpo.pe/pathogen.vim

#install [NERDTree](https://github.com/scrooloose/nerdtree)

git clone https://github.com/scrooloose/nerdtree.git ~/.vim/bundle/nerdtree

#copy vimrc
cp .vimrc ~/.vimrc
