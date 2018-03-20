---
title:  "Lattice Coding &amp; Crypto Meeting"
redirect_from: /2018/03/26/
---

Lattice-based approaches are emerging as a common theme in modern cryptography and coding theory. In communications, they are indispensable mathematical tools to construct powerful error-correction codes achieving the capacity of wireless channels. In cryptography, they are used to building lattice-based schemes with provable security, better asymptotic efficiency, resilience against quantum attacks and new functionalities such as fully homomorphic encryption.

This meeting — on *26 March 2018* — is aimed at connecting the two communities in the UK with a common interest in lattices. It will consist of several talks on related topics, with a format aimed at encouraging interaction.

## Program ##

### <span> 10:30 - 12:00 | [Carl Bootland](https://www.esat.kuleuven.be/cosic/carl-bootland/)</span>: Using non-integral bases to make better use of the plaintext space in homomorphic encryption schemes ###

In this talk I will present an encoding method for real numbers tailored for homomorphic function evaluation. Using a somewhat homomorphic encryption scheme allows one to compute simple arithmetic functions on encrypted data securely. Security constraints in all popular somewhat homomorphic encryption schemes necessitate the degree of the polynomial modulus to be large but with current encoding techniques the correctness requirement allows for much smaller values. As a result much of the plaintext space is left unused when using these encoding techniques. Our new generic encoding method uses expansions with respect to a non-integral base which allows one to exploit the full extent of the available plaintext space and reduces the growth of the coefficients when performing operations. This leads to better parameters and faster homomorphic function evaluation.

Joint work with Charlotte Bonte, Joppe W. Bos, Wouter Castryk, Ilia Iliashenko, Frederik Vercauteren:

Charlotte Bonte, Carl Bootland, Joppe W. Bos, Wouter Castryck, Ilia Iliashenko, Frederik Vercauteren, [Faster Homomorphic Function Evaluation using Non-Integral Base Encoding](https://eprint.iacr.org/2017/333), In Workshop on Cryptographic Hardware and Embedded Security, Lecture Notes in Computer Science, Springer-Verlag, pages 579–600, 2017.

### <span> 13:00 - 14:30 | [Xiaojun Yuan](http://sist.shanghaitech.edu.cn/faculty/yuanxj/)</span>: Fundamental Limits of Compute-Compress-and-Forward ###

Compute-and-forward (CF) harnesses interference by exploiting structured coding in wireless communication networks. The key idea of CF is to compute integer combinations of codewords from multiple source nodes, rather than to decode individual codewords by treating others as noise. Nested lattice codes are commonly used for efficient realization of CF. In this talk, we focus on how to forward the computed messages at relays in a wireless relay network. In general, these computed messages are correlated since they are combinations of a common set of source messages. As such, compression operations can be employed to enhance the spectral efficiency of the network. We show that the compression can be efficiently realized in a nested-lattice-coded network. Specifically, we present a compute-compress-and-forward (CCF) scheme where each relay compresses its computed message by taking quantization and modulo (QM) lattice operations. As an application, we explore the fundamental limits of CCF in a two-hop relay network with a single sink node. We show that CCF with multiple QM operations is optimal in the sense of achieving the minimum total compression rate. We also show that CCF is able to achieve the Slepian-Wolf rate region under certain conditions. We further show that most of the QM-operations involved in CCF can be realized in finite fields, so as to reduce the complexity involved in CCF. Numerical results are demonstrated to verify the superiority of CCF over CF.

### <span> 15:00 - 16:30 | [Thomas Prest](https://www.di.ens.fr/~prest/)</span>: The Rényi Divergence and Security Proofs ###

The Rényi divergence has recently found several applications in lattice-based cryptography, in which it often produces tighter proofs than the more classical statistical distance. However, it remains somewhat arcane to use because to its properties (or lack thereof, such as symmetry and triangle inequality).

In this talk, I will review recent advances regarding the Rényi divergence and provide an easy framework for establishing tight proofs using it. As an illustration, I will present examples in lattice-based cryptography for which the Rényi divergence allows significant gains. Finally, I will discuss open problems and potential future applications.

### <span> 16:45 - 18:15 | [Qifu Sun](https://www.researchgate.net/profile/Qifu_Sun)</span>: Lattice partition based physical-layer network coding ###

Physical-layer network coding (PNC) is a means to improve the throughput in wireless communication models. This talk will review the study of PNC based on the algebraic structure of lattice partitions. First, from an information-theoretical point of view, we compare the performance of lattice partition based PNC (LNC) with other transmission schemes such as routing, network-layer network coding, and analog network coding in a two-way relay network. Next, we revisit the classical algebraic framework of LNC in a more general wireless multiple-access relay network, in which two important research lines are the practical code design and the optimal selection of coding coefficients. For the practical code design, we emphasize on the LNC constructed from complex lattices over the ring of Gaussian integers and the ring of Eisenstein integers, and demonstrate its advantage over the LNC based on integer lattices by illustrating some particular design instances. For the optimal selection of coding coefficients, one main approach is to reduce it to the shortest vector problem (SVP) of a lattice. Though it is well known that a general SVP is NP-hard, we summarize the recent advances in the study of SVPs for LNC in the community, so that the particular SVPs can be efficiently solved.

### <span> 18:30 - | Workshop Dinner </span> ###

## Venue ##

<iframe src="https://www.google.com/maps/embed?pb=!1m14!1m8!1m3!1d2483.7481554015103!2d-0.1774244!3d51.4994889!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x0%3A0x31911b371c692e86!2sImperial+College!5e0!3m2!1sen!2suk!4v1457110930221" width="600" height="450" frameborder="0" style="border:0" allowfullscreen></iframe>

Room 611  
Department of Electrical and Electronic Engineering  
[Imperial College London](http://www.imperial.ac.uk/visit/campuses/south-kensington/)  
South Kensington  
London SW7 2AZ  

## Registration ##

Everyone is welcome. Two caveats:

1. Speakers are told the audience is somewhat familiar with lattices.
2. Please send us an email at <c.ling@imperial.ac.uk>, so that the size of the room fits with the
   number of participants.
