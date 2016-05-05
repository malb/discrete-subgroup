---
title:  "Lattice Coding &amp; Crypto Meeting"
redirect_from: /2016/05/04/
---

Lattice-based approaches are emerging as a common theme in modern cryptography and coding theory. In communications, they are indispensable mathematical tools to construct powerful error-correction codes achieving the capacity of wireless channels. In cryptography, they are used to building lattice-based schemes with provable security, better asymptotic efficiency, resilience against quantum attacks and new functionalities such as fully homomorphic encryption.

This meeting — on *4 May 2016* — is aimed at connecting the two communities in the UK with a common interest in lattices, with a long-term goal of building a synergy of the two fields. It will consist of several talks on related topics, with a format that will hopefully encourage interaction.

This event is also meant to celebrate the Centenary of Claude Shannon, who made profound contributions to information theory and cryptography.

## Program ##

We have four talks scheduled.


### <span>11:00–12:30 | Alister Burr:</span> Lattice coding and its Applications in Communications ###

> The talk will introduce Lattices and discuss their applications in wireless communications, starting with a brief introduction to the concept of lattices, and then some approaches to their construction, leading to the design of error-correcting codes based on lattices, including nested lattice codes. We will then discuss their application in multi-user, multihop wireless networks, and especially the concept of compute and forward.

### <span>13:30–15:00 | Nigel Smart:</span> Ring-LWE: An Efficient PQC Public Key Encryption Scheme ###

> I will outline, starting from first principles how an efficient public key encryption scheme can be built which is post-quantum secure. In particular I will touch on implementation aspects, cryptographic security, as well as the underlying hard lattice problems.

### <span>15:00–16:30 | Cong Ling:</span> [Achieving Channel Capacity with Lattice Codes](/discrete-subgroup/slides/2016-05-04-ling.pdf) ###

> Lattice coding is a new paradigm of modern coding theory, giving rise to coding schemes achieving the Shannon capacity of Gaussian-noise channels. In wireless communications, lattices have become an indispensable tool to construct powerful error-correction codes over mobile fading channels, thanks to the connection to algebraic number theory. This talk presents an overview of the constructions of lattice codes for Gaussian, fading and MIMO (multi-input multi-output) channels, and introduces a novel framework to achieve the capacity of fading/MIMO channels with ideal lattices.

- [Achieving AWGN Channel Capacity With Lattice Gaussian Coding](http://arxiv.org/abs/1302.5906)
- [Algebraic Lattice Codes Achieve the Capacity of the Compound Block-Fading Channel](http://arxiv.org/abs/1603.09263)

### <span>16:30–18:00 | Martin Albrecht:</span> [A Subfield Lattice Attack on Overstretched NTRU Assumptions](/discrete-subgroup/slides/2016-05-04-albrecht.pdf) ###

> We present work which exploits the presence of a subfield to solve the NTRU problem for large moduli $q$: norming-down the public key $h$ to a subfield may lead to an easier lattice problem, and any sufficiently good solution may be lifted to a short vector in the full NTRU-lattice.
>
> We restrict ourselves to choices of dimensions $n(λ)$ and modulus $q(λ)$ that were previously thought to offer resistance against attacks in time exponential in the security parameter $λ$. For any super-polynomial $q(λ)$, the subfield attack can be made sub-exponential in $λ$, or even polynomial as $q(\lambda)$ gets larger.
>
> The subfield lattice attack directly affects the asymptotic security of the bootstrappable homomorphic encryption schemes LTV and YASHE. It also makes GGH-like Multilinear Maps vulnerable to principal ideals attacks — therefore leading to a quantum break — and almost vulnerable to a statistical attack a-la Gentry-Szydlo. No *encodings of zero* nor *zero-testing parameter* are required.

- [A subfield lattice attack on overstretched NTRU assumptions: Cryptanalysis of some FHE and Graded Encoding Schemes](http://ia.cr/2016/127)

## Venue ##

<iframe src="https://www.google.com/maps/embed?pb=!1m14!1m8!1m3!1d2483.7481554015103!2d-0.1774244!3d51.4994889!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x0%3A0x31911b371c692e86!2sImperial+College!5e0!3m2!1sen!2suk!4v1457110930221" width="600" height="450" frameborder="0" style="border:0" allowfullscreen></iframe>

Room 611 (Dennis Gabor Seminar Room)  
Department of Electrical and Electronic Engineering  
[Imperial College London](http://www.imperial.ac.uk/visit/campuses/south-kensington/)  
South Kensington  
London SW7 2AZ  

## Registration ##

Everyone is welcome. Two caveats:

1. Speakers are told the audience is somewhat familiar with lattices.

2. Please send us an email at <c.ling@imperial.ac.uk>, so that the size
   of the room fits with the number of participants.
