You need to install PARI/GP to run this script : http://pari.math.u-bordeaux.fr/

Given a prime p, this variant of SIDH creates the parameters and stores them in a file. If the parameters are needed again (ie the same prime p is used), they will be fetched automatically and reused.

To run the program :
$ gp sidh_variant.gp

You can change the number of bits of the chosen characteristic at the end of the code.



