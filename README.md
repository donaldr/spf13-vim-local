spf13-vim-local
===============

My fork of David Brewer's dotfiles for local customization of the excellent spf13-vim vim distribution.

spf13-vim (https://github.com/spf13/spf13-vim) is a packaged vim configuration
distribution.  It supports customizing your local configuration via
.vimrc.local and .vimrc.bundles.local files in your home directory. 

This repo contains my local customizations of the distribution. Start by
installing spf13-vim using the instructions from the repo above. Then, install
these local customizations as follows:

    git clone https://github.com/donaldr/spf13-vim-local ~/.spf13-vim-local
    ~/.spf13-vim-local/create-symlinks.sh
