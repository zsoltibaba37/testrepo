# testrepo

This little program checks for the existence of the repository.

This script should be run before "mkrepo".

### Note

If you use it often you will receive the following message.

API rate limit exceeded for ×××.×××.×××.×××

#### Installation

You do not have to install it.

#### Files

testrepo

#### How to execute the script

First time I copy the file to the bin folder.
```sh
$ chmod +x testrepo
$ sudo cp -p testrepo /usr/local/bin
$ sudo chown root:root /usr/local/bin/*
```
Go to the folder what you want tested.
```sh
$ testrepo
```

