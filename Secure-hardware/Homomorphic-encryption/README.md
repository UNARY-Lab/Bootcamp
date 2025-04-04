# Scheme
Leveled/word-level schemes:
1. [BGV](https://dl.acm.org/doi/10.1145/2090236.2090262) - [Resource](https://www.inferati.com/blog/fhe-schemes-bgv#sec-keygen)

2. BFV: [paper1](https://eprint.iacr.org/2012/078) / [paper2](https://eprint.iacr.org/2012/144)

3. [CKKS](https://eprint.iacr.org/2016/421) - [Resource](https://blog.openmined.org/ckks-explained-part-1-simple-encoding-and-decoding/)

Fast bootstrapping/bit-level schemes:
1. [TFHE](https://eprint.iacr.org/2018/421) - [Resource](https://www.youtube.com/watch?v=npoHSR6-oRw&t=5610s)

2. FHEW: [paper1](https://eprint.iacr.org/2014/816) / [paper2](https://eprint.iacr.org/2022/198)


[A historical view](https://www.youtube.com/watch?v=487AjvFW1lk)

[A comparison](https://dl.acm.org/doi/abs/10.1007/978-3-030-81645-2_16)

# Framework
1. [Concrete](https://github.com/zama-ai/concrete)
2. [IBM HElayers](https://ibm.github.io/helayers/)
3. [HElib](https://github.com/homenc/HElib)
4. [SEAL](https://github.com/microsoft/SEAL)
5. [OpenFHE](https://www.openfhe.org/)


# Concept
## Number theoretic transform (NTT)
1. [Review 1](https://arxiv.org/abs/2306.12519)
2. [Review 2](https://ieeexplore.ieee.org/document/10177902)
3. [Survey](https://arxiv.org/abs/2211.13546)
4. [Code example](https://www.nayuki.io/page/number-theoretic-transform-integer-dft)
5. [Characterization](https://arxiv.org/abs/2012.01968)
6. [Video](https://www.youtube.com/watch?v=KIg2B0Ja02c)
7. [Software implementation](https://eprint.iacr.org/2018/039)
8. [Paper 1](https://eprint.iacr.org/2021/563)
9. [Paper 2](https://eprint.iacr.org/2016/504)


## Bootstrapping
1. [Overview](https://eprint.iacr.org/2023/149)
2. [BGV bootstrapping](https://eprint.iacr.org/2022/1363)
3. [TFHE bootstrapping](https://whitepaper.zama.ai/)


## Scheme switching
1. [BGGJ19](https://hal.science/hal-03228168)
2. [OpenFHE support](https://openfhe-development.readthedocs.io/en/latest/)

## Other common operations
1. [BConv](https://dl.acm.org/doi/abs/10.1007/978-3-030-10970-7_16): full-RNS version of CKKS
2. [ModUp](https://dl.acm.org/doi/abs/10.1007/978-3-030-10970-7_16)
3. [ModDown](https://dl.acm.org/doi/abs/10.1007/978-3-030-10970-7_16)
4. [keyswitching](https://dl.acm.org/doi/10.1007/978-3-030-40186-3_16): CKKS
5. [Decomp](https://dl.acm.org/doi/10.1007/978-3-030-40186-3_16): CKKS
6. [keyswitching inner product](https://dl.acm.org/doi/10.1007/978-3-030-40186-3_16): CKKS
7. [Automorphism](https://arxiv.org/abs/2109.05371)

# Research
|Design|Scope|Venue|Year|
|---|---|---|---|
|[BASALISC](https://eprint.iacr.org/2022/657)|BGV|TCHES|2023|
|[Survey](https://ieeexplore.ieee.org/document/10177902)|NTT|IEEE Access|2023|
|[F1](https://arxiv.org/abs/2109.05371)|FHE/NTT|MICRO|2021|
|[PipeZK](https://ieeexplore.ieee.org/document/9499783)|NTT/MSM|ISCA|2021|
|[AVX2 inst](https://eprint.iacr.org/2018/039)|NTT|Preprint|2018|
|[HEAX](https://dl.acm.org/doi/pdf/10.1145/3373376.3378523)|NTT|ASPLOS|2020|
|[BTS](https://dl.acm.org/doi/abs/10.1145/3470496.3527415)|FHE|ISCA|2022|
|[MAD](https://bu-icsg.github.io/publications/2023/Agrawal_MICRO_2023.pdf)|FHE|MICRO|2023|
|[BP-NTT](https://ieeexplore.ieee.org/document/10247691)|NTT|DAC|2023|
|[Survey](https://arxiv.org/abs/2303.10877)|Acc|arXiv|2023|
|[E3](https://eprint.iacr.org/2018/1013)|Compiler|arXiv|2018|
|[EVA](https://arxiv.org/abs/1912.11951)|Compiler|PLDI|2020|
|[HElium](https://arxiv.org/abs/2312.14250)|Compiler|arXiv|2023|

# Application
[A summary](https://dualitytech.com/blog/bootstrapping-in-fully-homomorphic-encryption-fhe/)


# Benchmark
1. [VIP-Bench](https://ieeexplore.ieee.org/document/9604804)
2. [IBM HElayers](https://ibm.github.io/helayers/)
3. [HElib](https://github.com/homenc/HElib)
4. [SEAL](https://github.com/microsoft/SEAL)


# Security measurement and metric
1. https://dl.acm.org/doi/10.1145/3297858.3304074
2. https://eprint.iacr.org/2022/204
3. [Tool to estimate LWE instances](https://github.com/malb/lattice-estimator)
4. [HE standard (check Table 1)](http://homomorphicencryption.org/wp-content/uploads/2018/11/HomomorphicEncryptionStandardv1.1.pdf)
5. [Paper on LWE Estimation](https://eprint.iacr.org/2015/046.pdf)
6. [Estimating the Security of HE](https://www.zama.ai/post/estimating-the-security-of-homomorphic-schemes)



# Contact
This file is maintained by faculties from ECE department at University of Central Florida.

| Scheme | Contact|
| ------ | ------ |
| BGV    | [Di Wu](https://www.unarylab.com) |
| CKKS   | [Sazadur Rahman](https://sazadur.github.io/) |
| TFHE   | [Xin Xin](https://xinx2013.github.io/) |
