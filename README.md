fingertree-tf
=============

A general sequence representation with arbitrary
annotations, for use as a base for implementations of
various collection types. This is an implementation modified
to use associated types instead of functional dependencies.

See the original paper
 * Ralf Hinze and Ross Paterson,
   \"Finger trees: a simple general-purpose data structure\",
   /Journal of Functional Programming/ 16:2 (2006) pp 197-217.
   <http://www.soi.city.ac.uk/~ross/papers/FingerTree.html>

For a tuned sequence type, see @Data.Sequence@ in the
@containers@ package, which is a specialization of
this structure.
                   
Examples are not available in this package. However I am
working on an @fingertree-extensible@ package which will use
an idea based on types a la carte to provide composable annotations 
and that package will include examples :D
