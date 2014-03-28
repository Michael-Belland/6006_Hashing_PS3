6006_Hashing_PS3
================

A repository with code that implements various hashing methods (linear probing, double hashing, and cuckoo hashing) in Python.

I provide code in PSET3.py that's clearly marked between comments like "# BEGIN YOUR CODE" and "## END STUDENT CODE".  AuxHashFunctions was provided by course staff, and takes a string character-by-character to add to the hash.  The hash is designed to avoid collisions between similar strings (like "ab" and "ba") by making each character's contribution not only dependent on its bit value (ord(c)) but also its location in the string (i).

Given the lists as described in the pset, the IMDB class can initialize given the 6905 film entries and 16588 actor entries, as well as calculate the career_impact as described in the problem set for around 30 popular actors in about 2.5 seconds.

Will be uploaded as soon as the official deadline for late submissions is passed; in order to not violate the collaboration policy for the course, I can't post this online before then.
