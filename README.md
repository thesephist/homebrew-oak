# [Oak](https://oaklang.org/) Homebrew Formulae

>_NOTE: Oak is [already included in the `homebrew-core` repository](https://github.com/Homebrew/homebrew-core/pull/103216) and comes with the default installation of Homebrew. This repository was useful before Oak was distributed with Homebrew, and may become useful for future changes to Oak, but is redundant for now._

Install Oak on your Mac or Linuxbrew-equipped computer:

```sh
brew tap thesephist/oak
brew install oak
```

Currently, the Oak formula does not install auxiliary language support files like the [vim syntax file](https://github.com/thesephist/oak/blob/main/tools/oak.vim). This may change, or we may instead find a way to facilitate installation of such things from the `oak` CLI itself (e.g. with a `oak setup vim-syntax` or something). This isn't decided yet, so the formula only installs the `oak` CLI itself.

