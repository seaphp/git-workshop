
# Basic Local Commands

## add

`-p | --patch`

Add individual changes of a file

```bash
$ git add -p README.md
```

## commit

`-a | --all`

Add all changes for tracked files

```bash
$ git commit -a
```

`--amend`

Update your previous commit with chance to edit the message

```bash
$ git commit --amend
```

## diff

`--staged`

compare the files in the index

```bash
$ git diff --staged filename.php
```

## status


`-uno | --untracked-files=no`

Prevent the display of untracked files

```bash
$ git status -uno
```
