---
title:  "Lattice Coding &amp; Crypto Meeting"
redirect_from: /2019/09/18/
---

Lattice-based approaches are emerging as a common theme in modern cryptography and coding theory. In communications, they are useful mathematical tools to construct powerful error-correction codes achieving the capacity of wireless channels. In cryptography, they are used to building lattice-based schemes with provable security, better asymptotic efficiency, resilience against quantum attacks and new functionalities such as fully homomorphic encryption.

This meeting — on Wednesday *18 September 2019* — is aimed at connecting the two communities with a common interest in lattices. It will consist of several talks on related topics, with a format aimed at encouraging interaction.

## Programme ##

### <span> 10:30 - 12:00 | [Thomas Debris](https://who.paris.inria.fr/Thomas.Debris/)</span>: [Wave: A New Family of Trapdoor One-Way Preimage Sampleable Functions Based on Codes]() ###

We present here a new family of trapdoor one-way functions that are Preimage Sampleable on Average (PSA) based on codes: the Wave-PSA family. Our trapdoor function is one-way under two computational assumptions: the hardness of generic decoding for high weights and the indistinguishability of generalized (U, U + V)-codes. Our proof follows the GPV strategy [GPV08]. By including rejection sampling, we ensure the proper distribution for the trapdoor inverse output. The domain sampling property of our family is ensured by using and proving a variant of the left-over hash lemma. We instantiate the new Wave-PSA family with ternary generalized (U, U + V)-codes to design a “hash-and-sign” signature scheme which achieves existential unforgeability under adaptive chosen message attacks (EUF-CMA) in the random oracle model. For 128 bits of classical security, signature sizes are in the order of 13 thousand bits, the public key size in the order of 3 megabytes, and the rejection rate is limited to one rejection every 10 to 12 signatures. 

### <span> 13:00 - 14:30 | [Sebastian Stern](https://www.uni-ulm.de/nt/staff/senior-researchers/stern/)</span>: [Complex and Quaternion-Valued Lattices for Digital Transmission]() ###

### <span> 15:00 - 16:00 | [Ayush Bhandari](https://www.imperial.ac.uk/people/a.bhandari)</span>: [The Unlimited Sensing Framework: Sampling and Reconstruction using Modulo Non-linearities]() ###

Almost all forms of data are captured using digital sensors or analog-to-digital converters (ADCs) which are inherently limited by dynamic range. Consequently, whenever a physical signal exceeds the maximum recordable voltage, the digital sensor saturates and results in clipped measurements. For example, a camera pointed towards the sun leads to an all-white photograph. Motivated by a variety of applications including scientific imaging, communication theory and digital sensing, a natural question that arises is: Can we capture a signal with arbitrary dynamic range?

In this work, we introduce the Unlimited Sensing framework which is a novel, non-linear sensing architecture that allows for recovery of an arbitrarily high dynamic range, continuous-time signal from its low dynamic range, digital measurements. Our work is based on a radically different ADC design, which allows for the ADC to reset rather than to saturate, thus producing modulo or folded samples.

In the first part of this talk, we discuss a recovery guarantee akin to Shannon’s sampling theorem which, remarkably, is independent of the maximum recordable ADC voltage. Our theory is complemented with a stable recovery algorithm. Moving further, we reinterpret the unlimited sensing framework as a generalized linear model and discuss the recovery of structured signals such as continuous-time sparse signals. This new sensing paradigm that is based on a co-design of hardware and algorithms leads to several interesting future research directions. On the theoretical front, a fundamental interplay of sampling theory and inverse problems raises new standalone questions. On the practical front, the benefits of a new way to sense the world (without dynamic range limitations) are clearly visible. We conclude this talk with a discussion on future directions and relevant applications.

### <span> 16:30 - 18:00 | [Subhayan Roy Moulik](https://www.cs.ox.ac.uk/people/subhayan.roymoulik/)</span>: []() ###

### <span> 18:30 - | Workshop Dinner </span> ###



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
2. Please send us an email at <martin.albrecht@royalholloway.ac.uk> to register.
