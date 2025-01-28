# zshellman

[![GitHub release](https://img.shields.io/github/release/Theile/zshellman.svg?style=plastic)](https://github.com/Theile/zshellman/releases)
[![GitHub license](https://img.shields.io/github/license/Theile/zshellman.svg?style=plastic)](https://github.com/Theile/zshellman/blob/master/LICENSE.md)
[![GitHub stars](https://img.shields.io/github/stars/Theile/zshellman.svg?style=plastic)](https://github.com/Theile/zshellman/stargazers)
[![GitHub issues](https://img.shields.io/github/forks/Theile/zshellman.svg?style=plastic)](https://github.com/Theile/zshellman/forks)
[![GitHub issues](https://img.shields.io/github/issues/Theile/zshellman.svg?style=plastic)](https://github.com/Theile/zshellman/issues)

## Sea Shell (zsh) scripting snippet

This fork will add Sea Shell (zsh) script snippets to the extension.

# Original shellman scripting snippet description

Learn easy Shell Scripting with `Shellman`, examples included. [Download](https://github.com/yousefvand/shellman-ebook) free ebook (pdf, epub). Reading the `Basics` part of the book is strongly recommended if you are new to `Shell Scripting`. Finally first edition of the ebook published.

Read [Shellman story on medium](https://medium.com/@remisa.yousefvand/shellman-reborn-f2cc948ce3fc) (3 min read).

![for in range](images/for.gif)

![math square root](images/math.gif)

![fn/fx: simple banner](images/banner.gif)

Instead of language specific syntax, here `Shell Scripting`, `Shellman` focuses on programming concepts. These concepts are grouped under `namespaces`. For example `string` namespace to name a few contains:

- concat
- length
- reverse
- toLower
- toUpper
- trim
- ...

to activate desired `snippet` you need to type `string` and select desired `snippet` from listed `snippets` i.e. `string reverse`. Using <kbd>TAB</kbd> key fill needed info and you are done.

Sometimes doing a job takes more than a `snippet`. `Shellman` has ready to use functions to put into your code if you type `fn`, and selected function usage is available after typing `fx`. For example the function to create a banner with desired text can be accessed via `fn banner simple` and to call this function the `snippet` is `fx banner simple`. Pass required parameters and a banner with your text would be printed.

### List of [commands](COMMANDS.md)

### [Full release Notes](CHANGELOG.md)

### [Contribution](nsroot/README.md)

### Latest release Notes

## 6.0.0

- `shellcheck` compatible (99.99%)
- Fixes issue #52, #53
