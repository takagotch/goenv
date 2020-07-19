### goenv
---

https://github.com/syndbg/goenv

```
```

``````go
# go
cd ~
git clone https://github.com/syndbg/goenv.git ~/.goenv
vi .bashrc
export GOENV_ROOT=#HOME/.goenv
export PATH=$GOENV_ROOT/bin:$PATH
eval "$(goenv init -)"

source ~/.bashrc   // exec $SHELL
goenv -v
goenv install -l
goenv versions

goenv global 1.8.3
goenv rehash
goenv versions
goenv version

vi ~/.bashrc
export GOPATH=$HOME/go
PATH=$PATH:$GOPATH/bin

source ~/.zshrc
mkdir -p $GOPATH/src/github.com/takagotch
cd $GOPATH/srcgithub.com/takagotch
git clone https://github.com/takagotch/tkyapp5

cd $GOENV_ROOT
git pull origin master
goenv install -l


```
