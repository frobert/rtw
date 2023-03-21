# rtw

## install rbenv

`git clone https://github.com/rbenv/rbenv.git ~/.rbenv`

For .bashrc:

`echo 'eval "$(~/.rbenv/bin/rbenv init - bash)"' >> ~/.bashrc`

For .bash_profile:

`echo 'eval "$(~/.rbenv/bin/rbenv init - bash)"' >> ~/.bash_profile `

For ZSH:

`echo 'eval "$(~/.rbenv/bin/rbenv init - zsh)"' >> ~/.zshrc `

Add to your .bashrc/.bash_profile/.zshrc

`eval "$(rbenv init -)"`

restart terminal

### install ruby build

`git clone https://github.com/rbenv/ruby-build.git "$(rbenv root)"/plugins/ruby-build `

### MAC homebrew

`brew install openssl@1.1 readline libyaml gmp `

## install ruby and rails

`rbenv install 3.2.1 --verbose `
`rbenv global 3.2.1 `
`gem install rails `

# Project

`bundle install `

## run rails server

`./bin/dev `
