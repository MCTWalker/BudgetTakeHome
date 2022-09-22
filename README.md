# Budget Take Home App
Ruby take home project

##Build Instructions

Written for Mac OS

Install homebrew if not already installed

###Install Ruby

Information obtained from: https://gorails.com/setup/osx/12-monterey

Run `brew install rbenv ruby-build`

Run `rbenv install 3.1.2`

Run `rbenv global 3.1.2`

If the global version doesn't change, add

`export PATH="$HOME/.rbenv/bin:$PATH"
eval "$(rbenv init -)"`

To your .zshrc file

Install Rails

Run `gem install rails -v 7.0.2.4`

Run `rbenv rehash`

You should now have the rails command available in your terminal
