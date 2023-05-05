# fermatdeffield
Fields of definition for the Picard group of the Fermat surface

The MAGMA file fieldofdef.magma gives a full classification of the field of definition L_n of the geometric Picard group of the Fermat surface of degree n. The output is fieldofdef.out, from which one reads L_n as follows for given n:
Let K = Q(mu_2n) be the 2n-th cyclotomic field. If n is even, adjoin an n/2-th root of 2. If n is divisible by 3, adjoin an n/3-th root of 3. For every d in fieldofdef.out which divides n, form the compositum with the listed number field M_d. The resulting field is L_n. (The list of integers given after each d are the torsion invariants of the abelian Galois group Gal(M_d)/K(mu_d).) 
