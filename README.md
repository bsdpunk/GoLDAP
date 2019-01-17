# LDAP and AD CLI viewer
A shell for AD and LDAP structures


## Description
View and Change LDAP and AD structures from the command line

## Usage
Must set several enviroment variables in your shell
```bash
LDAPServer
LDAPUser
LDAPBase
LDAPPassword
```

## Install
Readline.h is a requirement in unix enviroments, so readline-devel or readline-dev packages.

To install, use `go get`:

```bash
$ go get github.com/bsdpunk/GoLDAP
```
You may need to install other Libraries as well:
```bash
$ go get -d gopkg.in/ldap.v2
```

## Author

[bsdpunk](https://github.com/bsdpunk)
