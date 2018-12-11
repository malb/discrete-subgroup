---
title:  "Lattice Coding &amp; Crypto Meeting"
redirect_from: /2019/01/23/
---

Lattice-based approaches are emerging as a common theme in modern cryptography and coding theory. In communications, they are useful mathematical tools to construct powerful error-correction codes achieving the capacity of wireless channels. In cryptography, they are used to building lattice-based schemes with provable security, better asymptotic efficiency, resilience against quantum attacks and new functionalities such as fully homomorphic encryption.

This meeting — on Wednesday *23 January 2019* — is aimed at connecting the two communities with a common interest in lattices. It will consist of several talks on related topics, with a format aimed at encouraging interaction.

## Programme ##

### <span> 10:30 - 12:00 | [Fernando Virdia](https://pure.royalholloway.ac.uk/portal/en/persons/fernando-virdia(4ad6e099-9f70-4a5d-b0ac-cc37dd176547).html)</span>: Implementing RLWE-based Schemes Using an RSA Co-Processor ###

The transition to quantum-resistant cryptography will require designing, implementing, certifying and deploying new hardware capable of accelerating post-quantum cryptographic schemes. Given how slow this process can be, we look at the possibility of repurposing currently existing RSA/ECC co-processors for accelerating (ideal) lattice-based cryptography by exploiting the availability of fast long integer multiplication. Such co-processors are deployed in smart cards in passports and identity cards, secured microcontrollers and hardware security modules (HSM). In particular, we demonstrate an implementation of a variant of the Module-LWE-based Kyber Key Encapsulation Mechanism (KEM) that is tailored for high performance on a commercially available smart card chip (SLE 78).

### <span> 13:00 - 14:30 | [Patrick Solé](https://www.researchgate.net/profile/Patrick_Sole)</span>: Good Algebraic Codes Exist ###

We survey the algebraic structure and asymptotic performance of the self-dual and LCD classes of quasi-cyclic, quasi-twisted, and dihedral codes over finite fields and finite rings. Of special interest is the case of low index: double circulant codes and four circulant codes. An application to additive cyclic codes is given.

### <span> 15:00 - 16:30 | [Yang Yu](https://www.cwi.nl/people/yang-yu)</span>: Learning Strikes Again: The Case of the DRS Signature Scheme ###

Lattice signature schemes generally require particular care when it comes to preventing secret information from leaking through signature transcript. For example, the Goldreich-Goldwasser-Halevi (GGH) signature scheme and the NTRUSign scheme were completely broken by the parallelepiped-learning attack of Nguyen and Regev (Eurocrypt 2006). Several heuristic countermeasures were also shown vulnerable to similar statistical attacks. At PKC 2008, Plantard, Susilo and Win proposed a new variant of GGH, informally arguing resistance to such attacks. Based on this variant, Plantard, Sipasseuth, Dumondelle and Susilo proposed a concrete signature scheme, called DRS, that has been accepted in the round 1 of the NIST post-quantum cryptography project. In this work, we propose yet another statistical attack and demonstrate a weakness of the DRS scheme: one can recover some partial information of the secret key from sufficiently many signatures. One difficulty is that, due to the DRS reduction algorithm, the relation between the statistical leak and the secret seems more intricate. We work around this difficulty by training a statistical model, using a few features that we designed according to a simple heuristic analysis. While we only recover partial information on the secret key, this information is easily exploited by lattice attacks, significantly decreasing their complexity. Concretely, we claim that, provided that signatures are available, the secret key may be recovered using BKZ-138 for the first set of DRS parameters submitted to the NIST. This puts the security level of this parameter set below 80-bits (maybe even 70-bits), to be compared to an original claim of 128-bits. Joint work with Léo Ducas.

### <span> 16:45 - 18:15 | [Sanju Velani](https://pure.york.ac.uk/portal/en/researchers/sanju-velani(3b7d2e29-c243-4ed7-b284-c819e74101b7).html)</span>: TBC ###

### <span> 18:30 - | Workshop Dinner </span> ###

## Venue ##

**Note the changed venue.**

<iframe src="https://www.google.com/maps/embed?pb=!1m14!1m8!1m3!1d2483.7481554015103!2d-0.1774244!3d51.4994889!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x0%3A0x31911b371c692e86!2sImperial+College!5e0!3m2!1sen!2suk!4v1457110930221" width="600" height="450" frameborder="0" style="border:0" allowfullscreen></iframe>

Room 1109  
Department of Electrical and Electronic Engineering  
[Imperial College London](http://www.imperial.ac.uk/visit/campuses/south-kensington/)  
South Kensington  
London SW7 2AZ  

## Registration ##

Everyone is welcome. Two caveats:

1. Speakers are told the audience is somewhat familiar with lattices.
2. Please send us an email at <martin.albrecht@royalholloway.ac.uk> to register.
