keyex
=====

SSH Key Exchanger 

keyex configures public key authentication between multiple users and
hosts. It generates a new passphrase-less key pair if there not key
available. It takes care of adding keys to `.ssh/authorized_keys` and
host public keys to `.ssh/known_hosts`.

Exchange can be :
* N-N
* 1-N and back
* 1-N one way

keyex is written in Python and is released under the BSD 2-Clause
License.

Requirements
------------

* python
* paramiko

Tested on Debian Stretch with python 2.7 and paramiko 2.0.0.

