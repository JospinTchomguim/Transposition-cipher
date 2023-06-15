# Transposition-cipher
Program for encryption and decryption by transposition

A transposition cipher (or permutation cipher) is a cipher which consists in changing the order of the letters, therefore in constructing anagrams. This method has been known since ancient times, since the Spartans already used a scytale.

The transposition cipher requires the clear text to be split into blocks of equal size. The same permutation is then used on each of the blocks. The text may need to be completed (stuffing process) to allow this splitting. The encryption key is the permutation itself.

The number of possible permutations of a given length, which is the factorial of this length, therefore increases rapidly with it. For example, a three-letter word can only be permuted in 6 (=3!) different positions. Thus "col" can only be transformed into "col", "clo", "ocl", "olc", "lco" or "loc". When the number of letters increases, the number of arrangements increases rapidly and it becomes more difficult to find the original text without knowing the permutation, and without any knowledge of the plain text. So for a transposition cipher that uses blocks of 20 characters, there are 20! possibilities, so 2,432,902,008,176,640,000 combinations.
