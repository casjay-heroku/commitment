# About WTC (What The Commit)

Commitment is a small Tornado application that generates random commit messages.

<https://commitment.herokuapp.com/>

Commitment also provides <https://commitment.herokuapp.com/index.txt> which provides plain text output.  
Some interesting usage for that can be:

```
git config --global alias.yolo '!git commit -m "$(curl -s https://commitment.herokuapp.com/index.txt)"'
```

Or use the [WhatTheCommit](https://marketplace.visualstudio.com/items?itemName=Gaardsholt.vscode-whatthecommit) vscode extension

# License

This is a fork of <https://github.com/ngerakines/commitment>  
Copyright (c) 2010-2017 Nick Gerakines <nick@gerakines.net>  
Copyright (c) 2020 CasjaysDev <git-admin@casjaysdev.com>  
  
This project and its contents are open source under the [MIT license](LICENSE.md).  
