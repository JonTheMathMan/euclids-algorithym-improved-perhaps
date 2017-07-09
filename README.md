# euclids-algorithym-improved-perhaps
This is my variation of Euclid's algorithym for finding the greatest common factor.
The idea is that the modulus operation, which gives the remainder, can whittle off even more by noticing that the divisor minus the remainder should still contain the common factor. Or if a is the common factor: 3a - 2a = 1a HOWEVER 13a - 2*5a = 3a and 13a - 3*5a has an absolute value of ONLY 2a. NOTICE regular modulus gets 3a which is larger than 2a, so in some cases you can whittle down faster with this variation of Euclid's algorithym.
