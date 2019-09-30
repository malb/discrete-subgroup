---
title:  "Lattice Coding &amp; Crypto Meeting"
redirect_from: /2019/11/20/
---

Lattice-based approaches are emerging as a common theme in modern cryptography and coding theory. In communications, they are useful mathematical tools to construct powerful error-correction codes achieving the capacity of wireless channels. In cryptography, they are used to building lattice-based schemes with provable security, better asymptotic efficiency, resilience against quantum attacks and new functionalities such as fully homomorphic encryption.

This meeting — on Wednesday *20 November 2019* — is aimed at connecting the two communities with a common interest in lattices. It will consist of several talks on related topics, with a format aimed at encouraging interaction.

## Programme ##

### <span> 11:00 - 12:00 | [Ilia Iliashenko](https://www.esat.kuleuven.be/cosic/people/ilia-iliashenko/)</span>: [Sparse-secret Ring-LWE in FHE: is it really needed?]() ###

The most efficient fully homomorphic encryption schemes rely on a variant of the Ring-LWE problem with secret keys of a fixed and small Hamming weight. Such secrets allow faster FHE bootstrapping at the cost of weaker security guarantees. In this work we studied how how to perform bootstrapping without sparse secrets, thus avoiding this security loss in the HEAAN FHE scheme.

### <span> 13:0:00 - 14:30 | [Jan-Pieter D'Anvers](https://www.esat.kuleuven.be/cosic/people/jan-pieter-danvers/)</span>: [How dangerous are decryption failures in lattice-based encryption?]() ###

Many lattice-based encryption schemes are prone to a small decryption failure probability, where valid ciphertexts can not be decrypted. These failures leak information about the secret key and can thus be used to break the scheme. In this talk, we will examine how to optimize the search for decryption failures, and how to recover the secret using these failures.

### <span> 15:00 - 16:00| [Jianwei Li]()</span>: [Slide Reduction, Revisited -- Filling the Gaps in SVP Approximation]() ###

We show how to generalize Gama and Nguyen's slide reduction algorithm [STOC '08] for solving the approximate Shortest Vector Problem over lattices (SVP) to allow for arbitrary block sizes, rather than just block sizes that divide the rank $n$ of the lattice. This leads to significantly better running times for most approximation factors. We accomplish this by showing that a weaker notion of reduction (HSVP reduction) suffices for the first block of a slide-reduced basis and using the DBKZ algorithm of Micciancio and Walter [Eurocrypt '16] to achieve this notion.
    
We also show a different algorithm that works when the block size is quite large---at least half the total rank. This yields the first non-trivial algorithm for sublinear approximation factors. 
    
Together with some additional optimizations, these results yield significantly faster provably correct algorithms for $\delta$-approximate SVP for all approximation factors $n^{1/2+\eps} \leq \delta \leq n^{O(1)}$, which is the regime most relevant for cryptography. For the specific values of $\delta = n^{1-\eps}$ and $\delta = n^{2-\eps}$, we improve the exponent in the running  time by a factor of $2$ and a factor of $1.5$ respectively.

### <span> 16:30 - 18:00 | [Koen de Boer](https://www.cwi.nl/people/koen-de-boer)</span>: []() ###

## Venue ##

<iframe src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d1759.1081035542509!2d-0.5649690130036801!3d51.425935537279926!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x0%3A0xa284ace5bf4462fc!2sDepartment%20of%20Physics!5e0!3m2!1sen!2suk!4v1568123841951!5m2!1sen!2suk" width="600" height="450" frameborder="0" style="border:0;" allowfullscreen=""></iframe>

Tolansky 125  
[Royal Holloway](https://www.royalholloway.ac.uk/home.aspx), University of London  
Egham Hill  
Egham  
Surrey TW20 0EX

Royal Holloway

## Registration ##

Everyone is welcome. Two caveats:

1. Speakers are told the audience is somewhat familiar with lattices.
2. Please send us an email at <martin.albrecht@royalholloway.ac.uk> to register.
