# mxrepo

Simple helper script for working on multiple git repositories in a specific
directory.

This script is useful if you work with 'mxdev' sources for project
development or if you want to perform backups of a github account.

## Usage

Clone repositories:

```shell
mxrepo clone <CONTEXT> [<PACKAGE>]
```

Update repositories:

```shell
mxrepo pull [<PACKAGE>]
```

Backup of context:

```shell
mxrepo backup <CONTEXT>
```

Check repository state:

```shell
mxrepo status [<PACKAGE>]
```

Listing repository branch:

```shell
mxrepo branch [<PACKAGE>]
```

Show repository diff:

```shell
mxrepo diff [<PACKAGE>]
```

Commit all repository changes:

```shell
mxrepo commit "<MESSAGE>" [<PACKAGE>]
```

Push all committed changes:

```shell
mxrepo push [<PACKAGE>]
```

Discard all changes:

```shell
mxrepo checkout [<PACKAGE>]
```

## Copyright

- Copyright (c) 2025 mxstack Contributors
- BSD 2-clause license (see below)

## Contributors

- Robert Niederreiter
- Johannes Raggam
