# mxrepo

Simple helper script for working on multiple git repositories in a specific
directory.

This script is useful if you work with 'mxdev' sources for project
development or if you want to perform backups of a github account.

## Usage

For cloning repositories, use:
    mxrepo clone CONTEXT [PACKAGE]

For updating repositories, use:
    mxrepo pull [PACKAGE]

For backup of context, use:
    mxrepo backup CONTEXT

For checking repository state, use:
    mxrepo status [PACKAGE]

For listing repository branch, use:
    mxrepo branch [PACKAGE]

For showing repository diff, use:
    mxrepo diff [PACKAGE]

For committing all repository changes, use:
    mxrepo commit "MESSAGE" [PACKAGE]

For pushing all committed changes, use:
    mxrepo push [PACKAGE]

For discarding all changes, use:
    mxrepo checkout [package]

## Copyright

- Copyright (c) 2022-2024 mxstack Contributors
- BSD 2-clause license (see below)

## Contributors

- Robert Niederreiter
- Johannes Raggam
