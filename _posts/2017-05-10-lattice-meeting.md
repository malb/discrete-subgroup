---
title:  "Lattice Coding &amp; Crypto Meeting"
redirect_from: /2017/05/10/
---

Lattice-based approaches are emerging as a common theme in modern cryptography and coding theory. In communications, they are indispensable mathematical tools to construct powerful error-correction codes achieving the capacity of wireless channels. In cryptography, they are used to building lattice-based schemes with provable security, better asymptotic efficiency, resilience against quantum attacks and new functionalities such as fully homomorphic encryption.

This meeting — on *10 May 2017* — is aimed at connecting the two communities in the UK with a common interest in lattices, with a long-term goal of building a synergy of the two fields. It will consist of several talks on related topics, with a format that will hopefully encourage interaction.

## Program ##

### <span>10:30 - 12:00 | [Robert Fischer](https://www.uni-ulm.de/in/nt/staff/professors/fischer/):</span> [Lattice Reduction and Factorization for Equalization](/discrete-subgroup/slides/2017-05-10-fischer.pdf)###

In digital communications, signal constellations are usually drawn from a regular grid. Consequently, the mathematical tool of lattices is of great interest. Since more than one decade, equalization schemes based on the principle of lattice reduction, i.e., the selection of a suited basis, in which the equalization is carried out, are known to achieve the optimum diversity order with very low complexity. Recently, in the field of relaying, integer-forcing schemes have been proposed. Both approaches are tightly related to each other.

In the talk, an introduction to the concepts of lattice-reduction-aided and integer-forcing equalization is given. The respective mathematical background is studied and an overview on the different criteria and algorithms for solving the respective factorization problem is given.

### <span>13:00 - 14:30 | [Alexander May](http://www.cits.rub.de/personen/may.html):</span> [Recent Advances in Decoding Random Binary Linear Codes – and Their Implications to Crypto](/discrete-subgroup/slides/2017-05-10-may.pdf)###

This survey talk gives an overview of algorithms for decoding random linear codes. We start with Pranges information set decoding and Stern's meet-in-the-middle technique, and building on these algorithms we explain recent advances by May, Meurer, Thomae (Asiacrypt 2011), Becker, Joux, May, Meurer (Eurocrypt 2012) and May, Ozerov (Eurocrypt 2015) that led to significant improvements in the run time exponent. Moreover, we discuss implications for choosing cryptographic keys in code-based cryptography, also in the quantum setting.

### <span>15:00 - 16:30 | [Joseph Jean Boutros](http://www.josephboutros.org/):</span> [Construction - A Lattices with Number Fields](/discrete-subgroup/slides/2017-05-10-boutros.pdf) ###

Lattices are discrete sets of points in real or complex Euclidean spaces with a group structure. Lattices are an important tool for information processing in many areas such as cryptography, vector quantization, and channel coding. The recent success of building high-dimensional fast-decodable lattices from non-binary codes motivated us to investigate methods for building full-diversity lattices via Construction A (Leech & Sloane 1971). On the Gaussian channel, in absence of fading, low-density lattices from Construction A (LDA) can achieve Shannon capacity under lattice decoding (di Pietro 2014). Generalized low-density (GLD) lattices and LDA lattices are built from an error-correcting code over a finite field which is embedded and shifted in all directions in the Euclidean space to create a discrete group structure. Under iterative decoding, the finite field size is selected large enough to guarantee that the LDA/GLD lattice is not perturbed by its integer cubic sub-lattice. In presence of fading, cubic integer lattices are replaced by lattices from number fields. The LDA/GLD lattice for diversity forms a partition chain starting with the lattice from the ring of integers in the number field and ending with a lattice from an ideal in the ring of integers. The lattice diversity order is directly related to the signature of the number field. For fields of degree two and above, we show how to select the number field and the ideal for Construction A in order to make lattices that are good for both Gaussian and fading channels.

### <span>16:45 - 18:15 | [Thomas Johansson](http://portal.research.lu.se/portal/en/persons/thomas-johansson(f6c92fc5-826c-4c22-9c01-d9c9e2c9febd).html):</span> Combinatorial Methods for Solving LWE###

This survey talk gives an overview of combinatorial algorithms for solving the learning with errors (LWE) problem. We will discuss various problem instances of interest and then overview the BKW algorithm. We will present various improvements to BKW, including lazy modulus switching and coded-BKW (Albrecht, Faugère, Fitzpatrick, Perret, PKC 2014; Kirchner Fouque, Crypto 2015; Guo, Johansson, Stankovski, Crypto 2015).


## Venue ##

<iframe src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d2482.381665231909!2d-0.1362341486784799!3d51.52455917953798!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x48761b2f69173579%3A0xd008c67faecc133e!2sUniversity+College+London!5e0!3m2!1sen!2suk!4v1487758517334" width="600" height="450" frameborder="0" style="border:0" allowfullscreen></iframe>

MPEB 1.20  
UCL  
Department of Computer Science  
Gower St
Kings Cross  
London WC1E 6BT  

**Getting there:** follow [these directions](http://www.cs.ucl.ac.uk/getting_here/) but go to 1st floor instead of 5th floor.

## Registration ##

Everyone is welcome. Two caveats:

1. Speakers are told the audience is somewhat familiar with lattices.
2. Please send us an email at <martin.albrecht@royalholloway.ac.uk>, so that the size
   of the room fits with the number of participants.
