---
title:  "Lattice Coding &amp; Crypto Meeting"
redirect_from: /2019/11/20/
---

Lattice-based approaches are emerging as a common theme in modern cryptography and coding theory. In communications, they are useful mathematical tools to construct powerful error-correction codes achieving the capacity of wireless channels. In cryptography, they are used to building lattice-based schemes with provable security, better asymptotic efficiency, resilience against quantum attacks and new functionalities such as fully homomorphic encryption.

This meeting — on Wednesday *20 November 2019* — is aimed at connecting the two communities with a common interest in lattices. It will consist of several talks on related topics, with a format aimed at encouraging interaction.

## Programme ##

### <span> 11:00 - 12:00 | [Ilia Iliashenko](https://www.esat.kuleuven.be/cosic/people/ilia-iliashenko/)</span>: [Sparse-secret Ring-LWE in FHE: Is it Really Needed?]() ###

The most efficient fully homomorphic encryption schemes rely on a variant of the Ring-LWE problem with secret keys of a fixed and small Hamming weight. Such secrets allow faster FHE bootstrapping at the cost of weaker security guarantees. In this work we studied how how to perform bootstrapping without sparse secrets, thus avoiding this security loss in the HEAAN FHE scheme.

### <span> 13:0:00 - 14:30 | [Jan-Pieter D'Anvers](https://www.esat.kuleuven.be/cosic/people/jan-pieter-danvers/)</span>: [How Dangerous are Decryption Failures in Lattice-based Encryption?]() ###

Many lattice-based encryption schemes are prone to a small decryption failure probability, where valid ciphertexts can not be decrypted. These failures leak information about the secret key and can thus be used to break the scheme. In this talk, we will examine how to optimize the search for decryption failures, and how to recover the secret using these failures.

### <span> 15:00 - 16:00| [Jianwei Li]()</span>: [Slide Reduction, Revisited -- Filling the Gaps in SVP Approximation]() ###

We show how to generalize Gama and Nguyen's slide reduction algorithm [STOC '08] for solving the approximate Shortest Vector Problem over lattices (SVP) to allow for arbitrary block sizes, rather than just block sizes that divide the rank $n$ of the lattice. This leads to significantly better running times for most approximation factors. We accomplish this by showing that a weaker notion of reduction (HSVP reduction) suffices for the first block of a slide-reduced basis and using the DBKZ algorithm of Micciancio and Walter [Eurocrypt '16] to achieve this notion.
    
We also show a different algorithm that works when the block size is quite large---at least half the total rank. This yields the first non-trivial algorithm for sublinear approximation factors.
    
Together with some additional optimizations, these results yield significantly faster provably correct algorithms for $\delta$-approximate SVP for all approximation factors $n^{1/2+\eps} \leq \delta \leq n^{O(1)}$, which is the regime most relevant for cryptography. For the specific values of $\delta = n^{1-\eps}$ and $\delta = n^{2-\eps}$, we improve the exponent in the running  time by a factor of $2$ and a factor of $1.5$ respectively.

### <span> 16:30 - 18:00 | [Koen de Boer](https://www.cwi.nl/people/koen-de-boer)</span>: [The Continuous Hidden Subgroup Problem]() ###

In this talk, we consider the problem of finding the period lattice L of a periodic function f on R^m. This is a generalization of the hidden subgroup problem and is referred to as the continuous hidden subgroup problem. By means of the (discrete) quantum Fourier transform we obtain points in the dual of the period lattice L of f, though with errors due to the discreteness and finiteness of the quantum machine. In our work we show that these errors stay reasonably small, from which we can conclude that recovering the period lattice L can be done in quantum polynomial time. This talk focusses on (1) getting some intuition of the quantum algorithm and (2) giving some idea about how the errors behave in the case of a single dual lattice point.

Paper abstract (https://eprint.iacr.org/2019/716.pdf): The Hidden Subgroup Problem (HSP) aims at capturing all problems that are susceptible to be solvable in quantum polynomial time following the blueprints of Shor’s celebrated algorithm. Successful solu- tions to this problems over various commutative groups allow to effi- ciently perform number-theoretic tasks such as factoring or finding dis- crete logarithms. The latest successful generalization (Eisentrager et al. STOC 2014) con- siders the problem of finding a full-rank lattice as the hidden subgroup of the continuous vector space R^m , even for large dimensions m. It un- locked new cryptanalytic algorithms (Biasse-Song SODA 2016, Cramer et al. EUROCRYPT 2016 and 2017), in particular to find mildly short vectors in ideal lattices. The cryptanalytic relevance of such a problem raises the question of a more refined and quantitative complexity analysis. In the light of the in- creasing physical difficulty of maintaining a large entanglement of qubits, the degree of concern may be different whether the above algorithm re- quires only linearly many qubits or a much larger polynomial amount of qubits. This is the question we start addressing with this work. We propose a detailed analysis of (a variation of) the aforementioned HSP algorithm, and conclude on its complexity as a function of all the relevant param- eters. Incidentally, our work fills gaps left by the extended abstract of Eisentrager et al.

### <span> 18:00 - | Workshop Dinner </span> ###

## Venue ##

<iframe src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d1759.1081035542509!2d-0.5649690130036801!3d51.425935537279926!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x0%3A0xa284ace5bf4462fc!2sDepartment%20of%20Physics!5e0!3m2!1sen!2suk!4v1568123841951!5m2!1sen!2suk" width="600" height="450" frameborder="0" style="border:0;" allowfullscreen=""></iframe>

Tolansky 125  
[Royal Holloway](https://www.royalholloway.ac.uk/home.aspx), University of London  
Egham Hill  
Egham  
Surrey TW20 0EX

## Registration ##

Everyone is welcome. Two caveats:

1. Speakers are told the audience is somewhat familiar with lattices.
2. Please send us an email at <martin.albrecht@royalholloway.ac.uk> to register.
