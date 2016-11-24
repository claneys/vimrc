This is my vim configuration. I cleaned it up most of the stuff.

The `vimrc` file should be easy to understand and contains almost everything.

# Install

        git clone https://github.com/claneys/vimrc.git .vim
        ln -s .vim/vimrc .vimrc
        vim +PlugInstall +qall
        cd ~/.vim/plugged/vimproc.vim && make

for Haskell

        dnf install cabal-install
        cabal update
        cabal install ghc-mod

And you're done.
