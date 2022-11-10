# LAB2

TEST
DEV
Tell me how to remove them locally and remotely:
To delete a remote branch
git push origin :dev
git push origin :test
To delete a local branch
git branch -d dev
git branch -d test

Tell me how to checkout another branch without commit
changes:
using Git stach:
git stash drop [-q|--quiet] [<stash>]
git stash ( pop | apply ) [--index] [-q|--quiet] [<stash>]
git stash branch <branchname> [<stash>]

Tell me how to list tags:
git tag

Tell me how to delete tag locally and remotely:
To delete remote tag:
git push origin --delete v1.0
To delete local tags:
git tag -d v1.0

![alt text](https://www.globalsign.com/application/files/7416/3763/0034/General_Banner_WhatisIOT_4_APAC_2021_11_22.jpg)
