---
title:  "Lattice Coding &amp; Crypto Meeting"
redirect_from: /2016/09/21/
---

Lattice-based approaches are emerging as a common theme in modern cryptography and coding theory. In communications, they are indispensable mathematical tools to construct powerful error-correction codes achieving the capacity of wireless channels. In cryptography, they are used to building lattice-based schemes with provable security, better asymptotic efficiency, resilience against quantum attacks and new functionalities such as fully homomorphic encryption.

This meeting — on *21 September 2016* — is aimed at connecting the two communities in the UK with a common interest in lattices, with a long-term goal of building a synergy of the two fields. It will consist of several talks on related topics, with a format that will hopefully encourage interaction.

## Program ##

We have four talks scheduled.

### <span>11:00–12:30 | [Jean-Claude Belfiore](http://perso.telecom-paristech.fr/~belfiore/):</span> Ideal Lattices: Connections between number fields and coding constructions###

In this talk, we first remind some basics of ideal lattice constructions using both totally real fields and CM-fields. Then, we propose new constructions of famous ideal lattices guided by the regular construction of the underlying lattice. Some examples are given where we obtain ideal lattice constructions for the densest lattices in dimension 8, 12, 24 or 32. We also show that there are infinitely many ideal lattices equivalent to the Leech lattice. Finally, some applications of ideal lattices to the area of wireless communications will be given.

### <span>13:30–15:00 | Dan Shepherd:</span> TBD ###

### <span>15:30–16:30 | [Antonio Campello](http://www.ime.unicamp.br/~campello/):</span> Sampling Algorithms for Lattice Gaussian Codes ###

Lattice Gaussian distributions are useful tools for constructing efficient cryptographic primitives and capacity-achieving schemes for a number of wireless systems. A worth element towards practical implementations of these schemes is the ability of sampling from such distributions, whose support is an n-dimensional lattice in the Euclidean space.

In this talk, we will present fast specialized algorithms for sampling over lattices constructed from error-correcting codes. This includes the low dimensional lattices with the best coding gains, their duals, and the 24-dimensional Leech lattice. In the derivation of our algorithms, a number of results concerning the theta series of notable lattices will be discussed. Throughout the talk, we will highlight the important role of the theta series in Communications.

Based on joint work with J.-C. Belfiore (Huawei Technologies France)

### <span>16:30–17:00 | [Cong Ling](http://www.commsp.ee.ic.ac.uk/~cling/):</span>  Lattice Gaussian Sampling with Markov Chain Monte Carlo (MCMC)###

Sampling from a lattice Gaussian distribution is emerging as a common theme in various areas such as coding and cryptography. The default sampling algorithm—Klein’s algorithm yields a distribution close to the lattice Gaussian only if the standard deviation is sufficiently large. This talk is concerned with a new method based on Markov chain Monte Carlo (MCMC) for lattice Gaussian sampling, which converges to the target lattice Gaussian distribution for any value of the standard deviation. A number of algorithms will be presented, such as Gibbs and Metropolis-Hastings. A problem of central importance is to determine the mixing time. It is proven that some of these Markov chains are geometrically ergodic, namely, the sampling algorithms converge to the stationary distribution exponentially fast.

Based on joint work with Zheng Wang and Guillaume Hanrot. (See [http://arxiv.org/abs/1501.05757](http://arxiv.org/abs/1501.05757) and [http://arxiv.org/abs/1405.1623](http://arxiv.org/abs/1405.1623).)

### <span>17:00–18:30 | [Daniel Dadush](http://homepages.cwi.nl/~dadush/):</span> Solving SVP and CVP in 2<sup>n</sup> Time via Discrete Gaussian Sampling ###

We show $2^{n+o(n)}$-time algorithms for the Shortest Vector Problem and the Closest Vector Problem on n-dimensional lattices (improving on the previous best-known algorithm of Micciancio and Voulgaris, which runs in time $4^{n+o(n)}$). The algorithms use the elementary yet powerful observation that, by properly combining samples from a Gaussian distribution over the lattice, we can produce exact samples from a narrower Gaussian distribution on the lattice. We use such a procedure repeatedly to obtain samples from an arbitrarily narrow Gaussian distribution over the lattice, allowing us to find a shortest (and closest) vector.

The SVP algorithm and its analysis are quite simple in hindsight. The main technical tool is an identity on Gaussian measures with a simple geometric proof originally due to Riemann. We will also discuss some of the subtleties that come up in adapting it to the Closest Vector Problem (a seemingly harder problem).

Based on joint work with Divesh Aggarwal, Oded Regev and Noah Stephens-Davidowitz. (See [http://arxiv.org/abs/1412.7994](http://arxiv.org/abs/1412.7994) and [http://arxiv.org/abs/1504.01995](http://arxiv.org/abs/1504.01995).)

## Venue ##

<iframe src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d1243.8765077316743!2d-0.5655192407744337!3d51.425963498881174!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x487679fe20cbdb53%3A0xac3b237bbee065a9!2sArts+Bldg%2C+Egham%2C+Surrey+TW20+0EX!5e0!3m2!1sen!2suk!4v1466067157311" width="600" height="450" frameborder="0" style="border:0" allowfullscreen></iframe>

Arts Building Ground Floor Room 24  
[Royal Holloway](https://www.royalholloway.ac.uk/home.aspx), University of London  
Egham Hill  
Egham  
Surrey TW20 0EX

Everyone is welcome. Two caveats:

1. Speakers are told the audience is somewhat familiar with lattices.

2. Please send us an email at <martin.albrecht@royalholloway.ac.uk>,
   so that the size of the room fits with the number of participants.
