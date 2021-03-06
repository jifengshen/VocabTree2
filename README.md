VocabTree2, by Noah Snavely (snavely@cs.cornell.edu)
----------------------------------------------------

To build the VocabTree2 library, just do "make" from the top-level
directory.

This code is distributed under a FreeBSD license.  See the source code
for details.

Unfortunately, I can't assist much with problems with the code.

If you find this code useful for your project, please cite the
following paper:

  Sameer Agarwal, Noah Snavely, Ian Simon, Steven M. Seitz and Richard
  Szeliski.  "Building Rome in a Day."  In Proc. ICCV 2009.

How to run
----------

This code works with SIFT keys in the format produced by David Lowe's
sift binary.  There are three tools provided:

 - VocabLearn: build a vocabulary tree from a set of key files using k-means
 - VocabBuildDB: build an image database from a set of key files and a tree
 - VocabMatch: match and image to a database and retrieve a set of top matches

Example usages:

  > 
