---
title:  "Lattice Coding &amp; Crypto Meeting"
redirect_from: /2019/05/08/
---

Lattice-based approaches are emerging as a common theme in modern cryptography and coding theory. In communications, they are useful mathematical tools to construct powerful error-correction codes achieving the capacity of wireless channels. In cryptography, they are used to building lattice-based schemes with provable security, better asymptotic efficiency, resilience against quantum attacks and new functionalities such as fully homomorphic encryption.

This meeting — on Wednesday *8 May 2019* — is aimed at connecting the two communities with a common interest in lattices. It will consist of several talks on related topics, with a format aimed at encouraging interaction.

## Programme ##

### <span> 10:30 - 12:00 | [Mengfan Zheng](https://dblp.org/pers/z/Zheng:Mengfan)</span>: [TBC]() ###

### <span> 13:00 - 13:45 | [Petros Wallden](http://www.pwallden.gr/)</span>: [Computational Security for Quantum Protocols: How Classical Parties can Obtain a Secure
Access in the Quantum Internet]() ###

Frequently quantum cryptography is associated with information theoretic security (ITS) and specifically with ITS key expansion. However, this is a very limited view. In reality quantum protocols can offer other advantages such as better efficiency. In that setting, where the benefit from using quantum protocols comes in form of efficiency, it is meaningful to consider protocols that offer security guarantees based on computational assumptions. In this talk, after giving a brief introduction to quantum computing, I will give examples of computationally secure quantum protocols and focus on our recent work on how to enable a fully classical party to participate in quantum protocols (including delegated blind quantum computation) and why this is important. The primitive of delegated pseudo-secret random qubit generator will be introduced, and a protocol achieving this based on trapdoor one-way functions with extra properties will be given.

### <span> 13:45 - 14:30 | [Alex Cojocaru](https://www.inf.ed.ac.uk/people/students/Alexandru_Cojocaru.html)</span>: [QFactory from Learning With Errors]() ###

In this talk I delve further in the primitive PSRQG defined in the previous talk. I first give a concrete construction of the function required for the simplest construction (secure only against honest-but-curious adversaries), based on the Learning-With-Errors problem and the trapdoor function of Micciancio and Peikert. Then I will give the second protocol that is secure against malicious adversaries, giving also the intuition of the proof and the new, modified functions used.

### <span> 15:00 - 16:30 | [Roope Vehkalahti](https://people.aalto.fi/roope.vehkalahti)</span>: [TBC]() ###

### <span> 16:45 - 18:15 | [Sujoy Sinha Roy](https://www.cs.bham.ac.uk/~sinharos/)</span>: [Engineering Lattice-based Cryptography - From Single Core to Multicore-Multiprocessor
High-Performance Parallel Architectures]() ###

In recent years, several hard problems from lattice theory have become popular for constructing post-quantum PKC. Besides post-quantum cryptography, lattice-problems have been used to construct homomorphic encryption schemes. Homomorphic encryption has applications in privacy-preserving cloud computing: users can upload their encrypted data in the cloud and can still perform computation on the encrypted data. While in theory, lattice-based cryptography offers wide applicability and strong security, its real deployment in a wide range of computing devices faces several challenges.

I will talk about the challenges in computing polynomial arithmetic in a ring and the computational and architectural solutions to overcome these challenges. I will describe how our post-quantum PKC scheme SABER, which is a candidate in the ongoing NIST’s post-quantum standardization event, was constructed to achieve both strong security guarantee and efficiency. I will conclude my talk by presenting a methodology for designing high-performance parallel architectures for homomorphic computing on encrypted data in the cloud.

### <span> 18:30 - | Workshop Dinner </span> ###

## Venue ##

<iframe src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d2482.639424114085!2d-0.1317048842295599!3d51.519830879637205!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x48761b2df948f01d%3A0x26c5a650cb0f521a!2sRoyal+Holloway+University+of+London!5e0!3m2!1sen!2suk!4v1553607558218" width="600" height="450" frameborder="0" style="border:0" allowfullscreen></iframe>

Room: BEDSQ-1-03  
11 Bedford Square  
Bloomsbury  
London WC1B 3RF

## Registration ##

Everyone is welcome. Two caveats:

1. Speakers are told the audience is somewhat familiar with lattices.
2. Please send us an email at <martin.albrecht@royalholloway.ac.uk> to register.
