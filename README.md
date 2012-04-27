## Description

Manages rbenv plugins - add, list and remove. Only works on Ruby 1.9.

## Install

    $ mkdir -p $RBENV_ROOT/plugins
    $ git clone git://github.com/cldwalker/rbenv-plugin.git $RBENV_ROOT/plugins/rbenv-plugin
    $ gem install boson

## Usage

    $ rbenv plugin list
    gemset
    update
    $ rbenv plugin add cldwalker/rbenv-travis
    Cloning into '/Users/me/Developer/.rbenv/plugins/rbenv-travis'...
    remote: Counting objects: 41, done.
    remote: Compressing objects: 100% (26/26), done.
    remote: Total 41 (delta 14), reused 35 (delta 8)
    Unpacking objects: 100% (41/41), done.
    $ rbenv plugin list
    gemset
    travis
    update
    $ rbenv plugin rm travis
    Deleted travis plugin

## Todo

* Tests!

## Credits

Started on awesome @relevance fridays!
