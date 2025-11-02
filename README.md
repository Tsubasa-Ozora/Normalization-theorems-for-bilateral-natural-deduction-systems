# Normalization theorems for bilateral natural deduction systems
I'm sharing my master's thesis here. It was completed in 2023 under the supervision of PD Dr. Luca Tranchini. I would like to thank him for his guidance.

## Abstract:
Rumfitt presented a bilateral natural deduction system in [Rum00]. We
study the relationships between this system and two of its fragments that are
considered in programming language literature. The first fragment we consider
is from Abe and Kimura [AK22], the second is from Lovas and Crary [LC06].
Both develop lambda-calculi that correspond to these fragments and prove
their normalization.

In this thesis, we first study the relationship between Rumfitt’s system and
two of its fragments by giving embeddings and prove that these embeddings
preserve the reduction relation. Second, we prove the normalization of all three
systems in a uniform manner. Our proof strategy differs from those given in
[AK22, LC06]. We prove by induction over ranks that order the different kinds
of redexes. The uniformity of our approach illustrates how the proofs of the
fragments contribute to the proof of the full system. Lastly, we prove the
subformula property for the full system.

