Log into a FreeBSD jail
=======================
`jlogin` is a simple shell script that logs the user into a local FreeBSD jail by hostname, so you don't have to remember the jail's ID or internal name.

Installation
------------
Copy `jlogin` to somewhere in your `$PATH` or execute it directly.

Usage
-----
```sh
jlogin <hostname> [user]
```

* **hostname** is the hostname of the jail you wish to log into
* **user** is a the user you wish to log in as. If not specified then run as the user executing `jlogin`
