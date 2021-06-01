### Description

This repository is for source code for the paper 
"A Tapered Floating Point Extension for the Redundant Signed Radix 2 System Using the Canonical Recoding"
https://arxiv.org/abs/2105.14401v1
Actually all that here is a spreadsheet in Numbers and Excel format. 
The Excel version is automatically generated from the Numbers one. 

This version of the paper is preliminary, and there is already a small list of errata, see below. Please if you would send all errata found to me at my school address, lts0016@uah.edu, or open an issue, after checking the list below. 

Please voice any concerns, and I will try to reciprocate with care and attention. Thanks in advance for reviewing my work on floating point systems. 

### Errata

LOG BASE TWO:
The logarithm in Theorem II.1, and subsequently, is base-2, 
though this was not specified. 

MISSING MINUS: 
Eq. 17 should be x(m,n) = m \cdot 2^{n - |m| + 1}

EQUATION REFERENCE: 
In the proofs, there is a missing equation reference 
(also the persistent and annoying issue with the reference name to this proof, "Theorem I"
which I've tried to fix a million times before.)

LVALOM:
The reported values for the largest value (LVALOM, the first column) in the NONADJ 
system were derived from 1/3 times 2^(N+1) instead of 1/3 times 2^(N-1), as intended. 
This was a typo that is already corrected in the source spreadsheet here. 
