# Bootcamp on neuromorphic computing (Spiking Neural Network)

## Prerequisites
Install [UnarySim](https://github.com/diwu1990/UnarySim)

## Reading
[TRAINING SPIKING NEURAL NETWORKS USING LESSONS FROM DEEP LEARNING](https://arxiv.org/pdf/2109.12894.pdf)

[Hardware list](https://github.com/fabrizio-ottati/awesome-neuromorphic-hw)

## Concept
1. Data: spike
   - [rate coding](https://ieeexplore.ieee.org/document/9139000) Section II-A
   - [temporal coding](https://ieeexplore.ieee.org/document/9139000) Section II-B
   - [delta modulation](https://snntorch.readthedocs.io/en/latest/tutorials/tutorial_1.html#delta-modulation)
   - [More](https://dl.acm.org/doi/abs/10.1145/3546790.3546803)
2. Data generation: [comparison](https://github.com/diwu1990/UnarySim/blob/52683a42e210004531f53fa362a9dd1d900b6546/stream/gen.py#L147)
   - Try out [an example](https://github.com/diwu1990/UnarySim/blob/main/test/stream/test_stream_bsgen.py)


## Application
1. [Event camera](https://rpg.ifi.uzh.ch/research_dvs.html)
2. [Robotics](https://www.mdpi.com/2674-0729/2/1/2)
3. ...

**Questions**
1. Any other applications


## Algorithm
1. A full example of neuromorphic computing training pipeline
   - Try out [this](https://github.com/Intelligent-Computing-Lab-Yale/Rate-vs-Direct)
2. [Training with back-propagation](https://arxiv.org/abs/1901.09948) [[Surrogate gradient visualization](https://www.frontiersin.org/articles/10.3389/fnins.2018.00331/full)]
3. [Convert DNN to SNN](https://ieeexplore.ieee.org/document/9157578)
4. [Spike-timing-dependent plasticity](https://compneuro.neuromatch.io/tutorials/W2D3_BiologicalNeuronModels/student/W2D3_Tutorial4.html)

**Questions**
1. Pros and cons between training and convert
2. Pros and cons between directed coding and rate coding
3. Pros and cons between rate and temporal coding
4. Pros and cons between back-propagation and STDP for training


## Hardware
1. [Neurogrid (2014)](https://ieeexplore.ieee.org/document/6805187)
2. [TrueNorth (2015)](https://ieeexplore.ieee.org/document/7229264)
3. [Intel Loihi (2018)](https://ieeexplore.ieee.org/document/8259423)
4. [SpiNNaker2 (2021)](https://arxiv.org/abs/2103.08392)
5. [BrainScaleS2 (2022)](https://www.frontiersin.org/articles/10.3389/fnins.2022.795876/full)
6. [An analytical cost model](https://ieeexplore.ieee.org/document/9914608)
7. ...

**Questions**
1. Summarize the differences among the above hardware.


## Revision history
| Date | Revision | Name |
|---|---|---|
| 05/10/2023 | First commit. Add overview of concept, application, algorithm, and hardware | Di Wu |
| 05/10/2023 | Add STDP | Di Wu |
| 05/24/2023 | Add training tutorial from UCSC | Di Wu |
| 07/10/2023 | Add spike encoding paper | Di Wu |
| 09/12/2023 | Add visualization for surrograt gradient | Di Wu |
