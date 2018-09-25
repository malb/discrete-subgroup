---
title:  "Lattice Coding &amp; Crypto Meeting"
redirect_from: /2018/09/24/
---

Lattice-based approaches are emerging as a common theme in modern cryptography and coding theory. In communications, they are useful mathematical tools to construct powerful error-correction codes achieving the capacity of wireless channels. In cryptography, they are used to building lattice-based schemes with provable security, better asymptotic efficiency, resilience against quantum attacks and new functionalities such as fully homomorphic encryption.

This meeting — on *24 September 2018* — is aimed at connecting the two communities with a common interest in lattices. It will consist of several talks on related topics, with a format aimed at encouraging interaction.

## Programme ##

### <span> 10:30 - 12:00 | [Leo Ducas](https://homepages.cwi.nl/~ducas/)</span>: [The General Sieve Kernel and New Records in Lattice Reduction](/discrete-subgroup/slides/2018-09-24-ducas.pdf) ###

Sieving algorithms are asymptotically the fastest heuristic algorithms for solving the shortest vector problem, and therefore for solving other problems such as LWE or SIS, due to the Block-Korkine-Zolotarev lattice reduction algorithm (BKZ).

Until recently, sieving was considered as a function to be used as a blackbox SVP oracle inside BKZ. The works of Ducas (Eurocrypt 2018), and of Laarhoven and Mariano (PQCrypto 2018), however, proposed improvements to lattice reduction that go beyond this blackbox use of Sieve-style algorithms.

To formalise and generalise these new strategies, we propose the General Sieve Kernel (G6K, pronounced /ȝe.si.ka/), an abstract machine supporting a wide variety of lattice reduction strategies based on sieving algorithms. It is designed to minimise the sieving computation effort per reduction quality, and achieves this via mechanisms such as recycling and on-the-fly lifting. We provide a highly optimised, multi-threaded, tweakable, and open-source implementation of this stateful machine.

Finally, we apply G6K to various lattice challenges (SVP, LWE). Our work demonstrates that sieving significantly outperforms enumeration in dimensions achievable in practice.

Joint work with Martin R. Albrecht, Gottfried Herold, Elena Kirshanova, Eamonn Postlethwaite and Marc Stevens.

### <span> 13:00 - 14:30 | [Krzysztof Latuszynski](http://www2.warwick.ac.uk/fac/sci/statistics/staff/academic-research/latuszynski/)</span>: [Markov chain Monte Carlo: design and optimisation](/discrete-subgroup/slides/2018-09-24-latuszynski.pdf) ###

This talk will present Markov chain Monte Carlo, its motivation in statistics and its probabilistic underpinning. Design and properties of the popular MCMC algorithms, such as the Metropolis-Hastings, the Gibbs sampler, MALA and Hamiltonian Monte Carlo will be presented and their optimisation that underlines the design of adaptive MCMC methods will be discussed.

### <span> 15:00 - 16:30 | [James Howe](http://www.bris.ac.uk/engineering/people/james-howe/index.html)</span>: [Standard Lattice-Based Key Encapsulation on Embedded Devices](/discrete-subgroup/slides/2018-09-24-howe.pdf) ###

In 2016, Bos et al. proposed the key exchange scheme FrodoCCS, that is also a submission to the NIST post-quantum standardization process, modified as a key encapsulation mechanism (FrodoKEM). The security of the scheme is based on standard lattices and the learning with errors problem. Due to the large parameters, standard lattice-based schemes have long been considered impractical on embedded devices. The FrodoKEM proposal actually comes with parameters that bring standard lattice-based cryptography within reach of being feasible on constrained devices. In this talk, we show how we have taken the final step of efficiently implementing the scheme on a low-cost FPGA and microcontroller devices and thus making conservative post-quantum cryptography practical on small devices.

### <span> 16:45 - 18:15 | [Laura Luzzi](http://perso-etis.ensea.fr/luzzi/)</span>: [Algebraic reduction for low-complexity lattice decoding]((/discrete-subgroup/slides/2018-09-24-luzzi.pdf)) ###

High-performance lattice codes for wireless and multiple antenna channels can be designed using number fields and division algebras. However, the main drawback of algebraic lattice codes is their prohibitive decoding complexity under maximum likelihood decoding. Algebraic reduction is a special lattice reduction technique which exploits the additional multiplicative structure of these codes to allow for low-complexity decoding. More precisely, this technique consists in absorbing part of the channel into the code, by approximating the channel matrix with an element of the group of units of the ring of integers in the number field, or of the group of units of the maximal order in the division algebra. This talk will revisit previous work on algebraic reduction and discuss the advantages and challenges of this technique as well as some recent applications.

### <span> 18:30 - | Workshop Dinner </span> ###

## Venue ##

<iframe src="https://www.google.com/maps/embed?pb=!1m14!1m8!1m3!1d2483.7481554015103!2d-0.1774244!3d51.4994889!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x0%3A0x31911b371c692e86!2sImperial+College!5e0!3m2!1sen!2suk!4v1457110930221" width="600" height="450" frameborder="0" style="border:0" allowfullscreen></iframe>

Room 909  
Department of Electrical and Electronic Engineering  
[Imperial College London](http://www.imperial.ac.uk/visit/campuses/south-kensington/)  
South Kensington  
London SW7 2AZ  

## Registration ##

Everyone is welcome. Two caveats:

1. Speakers are told the audience is somewhat familiar with lattices.
2. Please send us an email at <conghui.li15@imperial.ac.uk>, so that the size of the room fits with the number of participants.
