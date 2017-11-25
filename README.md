# Language-Project

Design Document for Language Project

Taofik Aiyepola


**Problems to solve**

-Conduct a way to read ASCII text using the base 27-encoding

-Use cosine distance vector to differentiate the give language to other known languages

-Use trigram frequencies to identify the language that is presented in a given document

-3 character should correctly represent a trigram

-Only allow character such as lowercase letters, spaces and newLine (‘\n’)

**Other Functions**

-Trigram Frequency Vector - Uses ASCII characters to determine the element of the trigram

-Cosine Distance Function- evaluate the similarities, or distance, between vectors. Noting that consistency and quantity would determine how similar it is.

-Language Function - used to compare language frequencies to the file presented

-Main- For Milestone 1, once compiled, should take one command line argument in order of the trigram from ‘(space-space-space)’ to ‘zzz’ separate frequency by spaces. For milestone 2, selects the correct language after comparing the language frequency, trigram frequency and the cosine distance function.

**Files Needed**

-Cosine.cpp, langDetect.cpp, trigram.cpp, main.cpp

-Cosine.h, trigram.h

**Libraries Needed**

-Vector

-String

-Iostream & fstream

**Compiles Script**

-Will need to compile cosine.cpp, langDetect.cpp and trigram.cpp

-Will need to represent the trigram frequencies as vectors in the mathematical sense
