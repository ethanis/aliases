# Getting started

I have these utilities in `~/aliases`. If you want to have a similar setup as mine, you can get started with:

```bash
# clone the repo
$ git clone git@github.com:ethanis/aliases.git ~/aliases
# add ~/aliases to your PATH
$ echo PATH="export "$HOME/aliases:$PATH"" >> ~/.zshrc # or ~/.bashrc depending on your shell
$ source ~/.zshrc # or restart your shell
```

## Table of contents

[gcmco](#gcmco)

### gcmco

Easily denote co-authors in a commit message to give commit attribution in GitHub

#### Usage

```bash
$ gcmco "awesome commit message" "@co-author-one" "@co-author-two" (add as many co-authors as you need!)
=> git commit -m "awesome commit message" -m "co-authored-by: @co-author-one" -m "co-authored-by: @co-author-two"
```
