# Hepman-compression
This project made by Sapir Naugauker and Daniel bugdari.

change of the Hepman compression

The origin code is taken from the site - https://u.cs.biu.ac.il/~wisemay/compression/

When performing the compression use main-c.c and When decoders use main-e.c.

The program finds the ten most common characters in the file. Any other character (other than the top ten) will be changed to a common character whose ASCII is closest to it. if there are two common characters that are equally close, one above it and one below it, prefer the one below it.

It builds the Hepman tree for only the ten common characters and compresses the file according to the tree built.

Note that as an unavoidable consequence of this change, the decoded file will contain only the ten common characters and the decrypted file will be different from the original file.
