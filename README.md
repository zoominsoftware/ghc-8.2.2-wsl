# ghc-8.2.2-wsl
## Binary installer for GHC 8.2.2 on WSL Ubuntu 16.04 64 bit

This a binary installation tarball for a build of GHC 8.2.2 that is suitable
for use on Windows Subsystem for Linux, running Ubuntu 16.04 64 bits.

It was built on native Ubuntu 16.04 - not WSL - using

`./configure --disable-large-address-space`

The instructions for installation are the same as for the usual GHC
binary installation tarballs. See the file INSTALL inside the tarball
for details.

This installation is distributed under the same license under which
GHC itself is distributed. In particular, it comes with NO WARRANTY,
neither from us nor from the original distributors of GHC.
