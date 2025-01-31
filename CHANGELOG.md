#Releases

### v3.0.5

- Included pyascore functionality.
- Fixed a bug related to Comet when --accounts_mods T

### v3.0.4

- Fixed minor issue regarding printing auxilary list of additional PSMs when there are no open-groups

### v3.0.3

- Added a column that indicates whether the additionally reported PSMs exceed their corresponding group threshold.

### v3.0.2

- Fixed a small bug related to printing when no discoveries are made.

### v3.0.1

- Reverted dynamic level competition so that it is done on stem sequence.
- Added reporting feature of delta masses and variable mods of discovered peptides.

### v2.1.5

- Further bug fixes relating to MSFragger search files.

### v2.1.4

- Fixed up bugs relating to MSFragger search files.

### v2.1.1

- Added option to get q-vals.

### v2.1.0

- Corrected the dynamic level competition so that it clusters based on the neutral mass instead of charged mass.

### v2.0.0

- Fixed seed
- Simplified the CONGA tool so that the narrow variant of the PSM would be used prior to filtering instead of considering the open PSM
- Protein is now reported
- Most importantly, updated the dynamic level competition in order to consider delta masses.
- Prints version when python3 -m CONGA is called

### v1.0.1

The code for v1.0.1 was not properly commited so 1.0.1 was created.

### v1.0.0

Looks good for production. Fixed a bug relating to cases when no discoveries are found.

### v0.0.2

This is the initial release on PYPI

### v0.0.1

This is the initial release