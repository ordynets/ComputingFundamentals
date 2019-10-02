# Generating the Reverse Complement

Here's an example DNA sequence

`cagagcaagactctgtctaaataaataaattaattaaattaaaaaataaataaaattgatgttttaggctaggtgtggtggctcacgcctgtaatcccagcactttgggaggccaaagtaggtggatcacctgaggtcaggagttcgagaccagcctggccaacatggtgaaaccccatctctactaaaaatacaaaaattagccgggcatagtggcgcacacctgtaatcccagcaactcgggaggctgaggcaggagaatcgcttgaacccatgtggcaaaggttgctgtgagctgagatcacaccactgtactccagcctgggcgacagagcaagactgtgtctcaattaaaaaaaattgatatttttatcaggtattaactctgaaaatacaaaaattagccaggcgtgatggcccacacctgtaatcctagctactcgggaggctgaggcacgagaatcgcctgaacctaggaggtggaggttgcagtgagctgagattgtgacactgcactccagtctggtgacagagcgagaccctctcaaaaaaaaaaaagaaaagccgagggagagaaaccttcccatttagtctgtggcatgtgtcttcatgaattgcttaagctctcaaatgttctttcagtaatttaaactcttctgctggttttcctgggaagggtgctgtataatcacatattaatgagtctttatgtgataaccttgaacaggcacgtggaggagttcagccccagagctgtctacaccagtggtaaagcgtccagtgctgctggcttaacagcagctgttgtgagagatgaagaatctcatgagtttgtcattgaggctggagctttgatgttggctgataatgtaagaacattttacactcttcagtataaagaagtcagaatacccctaccctatcagtaaaggcctataagttaccattaaaaagatgtccttaaaaacagcattctcagctgggcgcggtggctcacacctttgtcccagtactttgggaagccgaggtgggtggatcacctgaggtcaggagttcgagaccagcctggccaacatggcgaaaacccattttctctactaaaaatacaaaaattagccgggcatggtggcgggtgcttgt`

Write a Python script to convert this to a reverse complement RNA sequence. So, you will need to:

(1) Reverse the order of the sequence.

(2) Generate the complementary sequence (G->C, C->G, T->A, A->T).

(3) Replace Ts with Us.