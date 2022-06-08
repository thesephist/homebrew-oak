# [Oak](https://oaklang.org/) Homebrew Formulae

Install Oak on your Mac or Linuxbrew-equipped computer:

```sh
brew tap thesephist/oak
brew install oak
```

Currently, the Oak formula does not install auxiliary language support files like the [vim syntax file](https://github.com/thesephist/oak/blob/main/tools/oak.vim). This may change, or we may instead find a way to facilitate installation of such things from the `oak` CLI itself (e.g. with a `oak setup vim-syntax` or something). This isn't decided yet, so the formula only installs the `oak` CLI itself.

>_NOTE: Oak is [currently PR'd to be included in the `homebrew-core` repository](https://github.com/Homebrew/homebrew-core/pull/103216), at which point this Tap will become unnecessary._

