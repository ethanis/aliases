# Getting started

I have these utilities in `~/aliases`. If you want to have a copy my setup, you can get started with:

```bash
# clone the repo
$ git clone git@github.com:ethanis/aliases.git ~/aliases
# add ~/aliases to your PATH
$ echo PATH="export "$HOME/aliases:$PATH"" >> ~/.zshrc # or ~/.bashrc depending on your shell
$ source ~/.zshrc # or restart your shell
```

## Table of contents

- [aliases](#aliases)
- [gcmco](#gcmco)
- [git-stats](#git-stats)
- [glolz](#glolz)
- [sourceit](#sourceit)

### aliases

Opens the `~/aliases` directory in VS Code (yeah - it's meta).

**Usage**

```bash
$ aliases
```

### gcmco

Easily denote co-authors in a commit message to give commit attribution in GitHub.

**Usage**

```bash
$ gcmco "awesome commit message" "@co-author-one" "@co-author-two" (add as many co-authors as you need!)
git commit -m "awesome commit message" -m "co-authored-by: @co-author-one" -m "co-authored-by: @co-author-two"
```

### git-stats

Get a quick view into the contributions to a git repo

**Usage**

```bash
$ git-stats
Ethan Dennis	41 additions, 4 deleted, 37 total
```

### glolz

Pretty print a git log.

**Usage**

```bash
$ glolz
* c554785 - (HEAD -> master, origin/master) Add git-stats command (19 minutes ago) <Ethan Dennis>
* ec4823f - Add setup instructions (6 hours ago) <Ethan Dennis>
...
```

### sourceit

Source all the things files that may be setting shell state.

**Usage**

```bash
$ sourceit
Sourced all the things!
```
