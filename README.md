# WARNING!

DO NOT USE THIS UNLESS YOU KNOW WHAT YOU ARE DOING

It will add new HX region which does not define any limitaions.

USE IT FOR TESTING PURPOSE ONLY!

## Disclaimer
Using a wifi device outside the ranges your local law defines could
get your into trouble.

# Description

This repository contains the plain text version of the regulatory
database file I maintain for use with Central Regulatory Database
Agent daemon.  Also included is the compiled binary version of this
file signed with my RSA key.  This represents a good faith attempt
to capture regulatory information that is correct at the time of its last
modification.  This information is provided to you with no warranty
either expressed or implied.

Also included are the tools used to compile and sign the regulatory.bin
file as well as a MoinMoin macro used for viewing the database.

# Technical information

The regulatory information in `db.txt' is stored in a human-readable
format which can be read using the `dbparse.py' python module. This
python module is used by the web viewer (Regulatory.py) which is
implemented as a MoinMoin macro (and used on http://wireless.kernel.org)
to allow viewing the database for verification.

The dbparse module is also used by db2bin.py, the `compiler', which
compiles and signs the binary database.

For more information, please see the CRDA git repository:

	git://git.kernel.org/pub/scm/linux/kernel/git/mcgrof/crda.git

John W. Linville
17 November 2008
