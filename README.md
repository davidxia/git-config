# About

This repo versions my git configuration so that I can easily replicate my git settings
across all computers. And setting up a new computer for development is fast.

It works by creating a symlink from the user's home directory to the versioned `gitconfig`
file which has aliases and settings I like (e.g. autorebasing on pull). The `gitignore_global`
ignores compiled source files, packages, logs, databases, and OS and Vim-generated files.

# Installation

    git clone https://github.com/davidxia/git-config.git ~/.git-config
    ln -s ~/.git-config/gitconfig ~/.gitconfig
    ln -s ~/.git-config/gitignore_global ~/.gitignore_global

If you are not David Xia, make sure to change the name and email address in `gitconfig`.
