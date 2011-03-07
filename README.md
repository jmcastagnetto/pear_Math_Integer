Math_Integer
===========

The class Math_Integer can represent integers bigger than the
signed longs that are the default of PHP, if either the GMP or
the BCMATH (bundled with PHP) are present. Otherwise it will fall
back to the internal integer representation.

The Math_IntegerOp class defines operations on Math_Integer objects.

This is old code I wrote for [PEAR](http://pear.php.net). 
Originally it was tracked in CVS, then it was moved to SVN, 
and now I am importing it to git :-)

-- Jesus M. Castagnetto
