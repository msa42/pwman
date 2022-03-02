# pwman - manage secure passwords

-- *password management for anonymous identity*

## requirements

* openssl >= 3.0
* pwgen

## usage

You are strongly encouraged to read "[Passwords derivation using OpenSSL 3 (SCRYPT) and PWGEN](https://medium.com/@msa42/passwords-derivation-using-openssl-3-scrypt-and-pwgen-b7c07d2769eb)" which provides important guidelines and an analysis of the implementation.

1. Add a new passphrase by running `pwman-add`
2. You can now query an infinite stream of passwords using `pwman` (ie. `pwman github.com`)
