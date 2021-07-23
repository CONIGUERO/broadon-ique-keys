## BroadOn Keys

This repository contains BroadOn's root CA keys for their PKI infrastructure designed for the iQUe, and other certs and keys used for the same purpose.


# About SecurityWorlds

The `SecurityWorlds` folder contains a complete dump of the nShield HSMs used by BroadOn (and sometimes Nintendo) to hold the private keys used in production environments. They contain keys for the root, manufacturing, server, e-card, software and content CAs, as well as the keys for the actual certificates on the hierarchy level below those CAs.
All the data is stored encrypted in the `world` file. The operator and admin card dumps in the same directory can be used to decrypt it, provided one has the appropiate software.

## Missing keys

Some keys, like manufacturing CA and signing, are missing. However, they can be located inside the dumped security worlds. If you have the needed software, please don't hesitate to open a pull request with the missing keys in unencrypted PEM format.


