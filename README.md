# computational-complexity

# NTM
A nondeterministic Turing machine is like a deterministic Turing machines but with two transition functions. 

# Class NTIME 
NTIME(t(n)) is the set of all decision problems that can be solved by a nondeterministic Turing machine inin c.t(n) time , where t(n) is a function of the input size n, c is a constant . 

# Diagonalization
Diagonalization refers to a class of techniques used in complexity theory to separate complexity classes.

# cook
All NP-hardness results ultimately derive from the Cook-Levin theorem
# probabilistic Turing machine
a nondeterministic TM is also a TM with two transition functions. Thusa PTM is syntacticallysimilar.
The main difference between an NDTM anda PTM lies in how we interpret the graph of all possible computations: An NDTM is saidto accept the input if there exists a branch that outputs 1, whereas in the case of a PTM we consider the fraction of branches for which this happens.
a probabilistic algorithm will allow it to output a wrong answer with some small probability

we show how to reduce the probability of error to a minuscule quantity.

# BPP aims to capture efficient probabilistic computation
BPP, like P, is still a class capturing complexity on worst-case inputs.

The class BPP captures what we call probabilistic algorithms with two-sided error. That is, it allows an algorithm for a language L to output (with some small probability) both 0 when x ∈ L and1 when x not ∈ L.

Since a deterministic TM is a special case of a PTM(where both transition functions are equal), the class BPP clearly contains P.

there is a waytotransform every probabilistic algorithm to a deterministic algorithm while incurring only a polynomial slowdown.
# RP
Note that RP ⊆ NP,since every accepting branch is a“certificate” that the input is in the language
# ZPP
expected running time

# RP⊆NP
![image](https://github.com/user-attachments/assets/bd406446-445b-45f6-94f8-df0aca43ce7b)

# ZPP = RP∩coRP

#  PCP（probabilistically checkable proofs）
The PCP Theorem implies that for many NP optimization problems, computing near-optimal solutions is no easier than computing exact solutions.
By showing that even computing approximate solutions to many of these problems is NP-hard, the PCP Theorem extends the practical importance of the theory of NP-completeness。


The statement of thePCP TheoremallowsverifiersfordifferentNP languagestouse
a different number of query bits (so long as this number is constant). However, since
everyNPlanguageispolynomial-timereducibletoSAT,allthesenumberscanbeupper
boundedbyauniversalconstant,namely,thenumberofquerybitsrequiredbyaverifier
forSAT.

# Exponential Time Hypothesis (ETH)
![image](https://github.com/user-attachments/assets/5254d3ba-ce8e-41c0-bbb2-1d5c049689a0)


# variable forgetting  AKA variable elimination
Forgetting is removing variables from a logical formula while preserving the constraints on the other variables.

## universal elimination
