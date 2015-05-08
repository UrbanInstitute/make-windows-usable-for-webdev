# *Guide* : Making Windows not terrible for web development

## Installing Git + NodeJS

Grab the installers for (git)[http://git-scm.com/] and (node)[https://nodejs.org/]. Make sure to add the commands to the global path when asked to in the installers.

## Setting up a [Bash](http://en.wikipedia.org/wiki/Bash_%28Unix_shell%29) console

There are many terminal emulators out there which are pretty good, I ended up following [this tutorial](https://scotch.io/tutorials/get-a-functional-and-sleek-console-in-windows) which uses [ConEmu](https://github.com/Maximus5/ConEmu) and git bash (included with git).

## Create a bash profile with some nice startup stuff

In your users folder (for me this was `D:\Users\BSouthga`) create a file called `.bashrc`. In this file you can set different startup configuration values. I ended up just using to set some alias values,

```shell
alias subl='D:\\Sublime\ Text\ 3\\sublime_text.exe'
alias sas='C:\\Program\ Files\\SAS\\SASFoundation\\9.2\\sas.exe'
alias stata='\\\\uiad2\\WINAPPS\\stata13\\StataMP-64.exe'
alias phantomjs='D:/phantomjs-1.9.8-windows/phantomjs.exe'
alias serve='python -m SimpleHTTPServer'
alias gnuplot='D:\\gnuplot\\bin\\gnuplot.exe'
alias chrome='C:\\Program\ Files\ \(x86\)\\Google\\Chrome\\Application\\chrome.exe'
PYTHON=d:/Users/BSouthga/AppData/Local/Continuum/Anaconda/python/python.exe
```

This article has a more detailed example of a bash profile config : http://natelandau.com/my-mac-osx-bash_profile/

## Install a nice python distribution

Node will sometimes need python (and its just a great language to have!). I think the [Anaconda distribution](https://store.continuum.io/cshop/anaconda/) is great because it comes bundled with a bunch of scientific computing stuff and is easy to update.

