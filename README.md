# RCDataManagement

This repository contains several scripts for downloading, installing, and using data management tools on the Princeton Research Computing (RC) systems. Included are:

- Download and installation scripts for:
  - md5deep: a parallel checksumming tool that uses the md5sum checksum algorithm
  - pixz: parallel compression tool that speeds up compression and decompression using the XZ compression algorithm
  - veritar: an archive verification tool that uses the md5sum checksum algorithm to check that the contents of a tar.xz archive are consistent with a list of checksums
 
- Predefined `bash` functions that combine the above tools for useful compression, verification, and checksumming
- A python script that allows one to check consistency between two lists of checksums produced by these tools.

## Installation scripts
The main tools we will use are `md5deep`, `pixz`, and `veritar`. These will require a ptyhon environment based on `pyhon2.7`, along with other python libraries. To install this on an RC cluster
