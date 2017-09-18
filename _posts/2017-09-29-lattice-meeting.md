---
title:  "Lattice Coding &amp; Crypto Meeting"
redirect_from: /2017/09/29/
---

Lattice-based approaches are emerging as a common theme in modern cryptography and coding theory. In communications, they are indispensable mathematical tools to construct powerful error-correction codes achieving the capacity of wireless channels. In cryptography, they are used to building lattice-based schemes with provable security, better asymptotic efficiency, resilience against quantum attacks and new functionalities such as fully homomorphic encryption.

This meeting — on *29 September 2017* — is aimed at connecting the two communities in the UK with a common interest in lattices, with a long-term goal of building a synergy of the two fields. It will consist of several talks on related topics, with a format that will hopefully encourage interaction.

## Program ##

### <span>10:30 - 12:00 | [Martin Widmer](http://www.ma.rhul.ac.uk/mwidmer/):</span> Counting Lattice Points ###

In this talk we discuss the problem of counting lattice points in a given bounded subset of Euclidean space. If the set is sufficiently "nice" one expects that the ration of volume and lattice determinant is a reasonable estimate for this cardinality. But what exactly does “nice” mean here, can one find such “niceness-conditions” that are mild and easy to check in practise, and what quantities of the lattice and the set does the error term depend on? What can we say more when the lattice is admissible (e.g. the Minkowski-embedding of an ideal of a totally real number field) or at least “almost“ admissible? We hope to answer all of these questions .

### <span>13:00 - 14:30 | [Ram Zamir](https://www.eng.tau.ac.il/~zamir/):</span> Lattices in Information Theory ###

A lattice is a discrete subgroup of the Euclidean N-dimensional space, which is closed under regular addition and reflection.

Lattices provide useful analytical and algorithmic tools for designing codes for digital communication. In particular, lattice codes are used for analog-to-digital conversion, a problem known also as "vector quantization" or "lossy source coding". In the dual "channel coding" problem, lattice codes combine coding and modulation for noise immunity in transmitting digital data over the additive white-Gaussian noise channel. More recently, lattice codes were found useful for multi-user communication, in setups such as coding with side information, interference cancellation, network coding, and more.

What is a good lattice? how do we know it exists? how can we construct it? The figure of merit depends, in fact, on the application. In the talk we shall assess lattice goodness for each of the communication problems above, and show the existence of asymptotically good lattices as the dimension N becomes large. We prove the existence result in two ways: first, indirectly, using the Minkowski-Hlawka theorem; second, by randomizing a linear-code based lattice construction ("construction A").

### <span>15:00 - 16:30 | [Gottfried Herold](http://www.cits.rub.de/personen/herold.html):</span> Lattice Sieving ###

One of the main approaches to solve the Shortest Vector Problem (SVP) on lattices is Lattice Sieving, which heuristically solves SVP in exponential (in the lattice rank) running time and memory. In the algorithm originally proposed by M. Ajtai, R. Kumar and D. Sivakumar, we combine pairs of lattice points to form ever shorter lattice points. It achieves an asymptotic complexity of 2^0.415n time and 2^0.208n memory to solve SVP, ignoring subexponential factors.

There are currently two known techniques to asymptotically improve the complexity or to provide more flexible time-memory trade-offs: The first one is to use techniques from Locality Sensitive Hashing, due to A. Becker, L. Ducas, N. Gama and T. Laarhoven. The second technique is to combine more than two lattice points at a time, due to S. Bai, T. Laarhoven and D. Stehle, which was later improved by G. Herold and E. Kirshanova.

In this talk, I will first present an overview over those techniques. Then I will explain a recent result, obtained jointly with E. Kirshanova and T. Laarhoven, how to improve further on the results from Herold and Kirshanova and how to combine the two techniques to get even better time-memory trade-offs. If time permits, I will talk about implementation challenges and open problems.

### <span>16:45 - 18:15 | [Rachel Player](https://pure.royalholloway.ac.uk/portal/en/persons/rachel-player(67c61108-84bc-4e79-80ba-59a328b011f9).html):</span> Parameter Selection in Ring-LWE-based FHE ###

Fully Homomorphic Encryption (FHE) is one of the flagship applications of lattice-based cryptography. Several FHE schemes are based on the Ring Learning with Errors (Ring-LWE) problem. The underlying Ring-LWE instances used in these schemes are however somewhat different from ’typical’ Ring-LWE instances, so the FHE setting is interesting from the point of view of security. Another key issue in the FHE setting is that the choice of parameters also influences the inherent noise, a feature present in all FHE ciphertexts, which must be kept below a certain threshold or else decryption will fail. Good understanding of the noise growth behaviour is therefore essential to ensure correctness. In this talk we discuss the challenge of picking parameters in the FHE setting, balancing the requirements of security, performance and correctness.

## Venue ##

<iframe src="https://www.google.com/maps/embed?pb=!1m14!1m8!1m3!1d2483.7481554015103!2d-0.1774244!3d51.4994889!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x0%3A0x31911b371c692e86!2sImperial+College!5e0!3m2!1sen!2suk!4v1457110930221" width="600" height="450" frameborder="0" style="border:0" allowfullscreen></iframe>

Room 909B  
Department of Electrical and Electronic Engineering  
[Imperial College London](http://www.imperial.ac.uk/visit/campuses/south-kensington/)  
South Kensington  
London SW7 2AZ  

## Registration ##

Everyone is welcome. Two caveats:

1. Speakers are told the audience is somewhat familiar with lattices.
2. Please send us an email at <c.ling@imperial.ac.uk>, so that the size of the room fits with the
   number of participants.
