**l** - Indicates the type of fingerprint we will implement in the following order:

0 - Morgan Fingerprint: requires a specific value of s

1 - Bit-vector based: requires a specific value of s

2 - FeatMorgan: requires a specific value of s

3 - Bitvectors: requires a specific value of s

4 - MACCS: only requires the SMILES vector

5 - RDKit default: requires a specific value of t

6 - Linear: requires a specific value of t

7- Atom_pairs: only requires the SMILES vector

8 - Topological torsion: only requires the SMILES vector

9 - Bit vectors with torsion: only requires the SMILES vector

10 - Avalon: requires a specific value of k

11 - Avalon counts: requires a specific value of k

**t** - Functions as the number of bits we want to use, typically t = 4, 5, 6, or 7. If the protocol we use does not require a specific number of bits, we can fill this argument with any numerical value.

**s** - Dictates the order of magnitude when using the Morgan Fingerprints protocol, considering s = 0, 1, 2, or 3.

**k** - Represents the number of bits for Avalon and Avalon counts, where k = 512 or 1024.
