---
title: "Video Representation Learning by Recognizing Temporal Transformations"
collection: publications
permalink: /publication/2020-temporal-ssl
date: 2020-07-01
venue: 'European Conference on Computer Vision 2020'
citation: 'S. Jenni, G. Meishvili, and P. Favaro. &quot;Video Representation Learning by Recognizing Temporal Transformations.&quot; In <i>ECCV 2020</i>.'
---

[[PDF]](https://arxiv.org/pdf/2007.10730.pdf) [[Project Page]](https://sjenni.github.io/temporal-ssl/) [[Code]](https://github.com/sjenni/temporal-ssl) 

## Abstract

We introduce a novel self-supervised learning approach to learn representations of videos that are responsive to changes in the motion dynamics. Our representations can be learned from data without human annotation and provide a substantial boost to the training of neural networks on small labeled data sets for tasks such as action recognition, which require to accurately distinguish the motion of objects.
We promote an accurate learning of motion without human annotation by training a neural network to discriminate a video sequence from its temporally transformed versions. To learn to distinguish non-trivial motions, the design of the transformations is based on two principles: 1) To define clusters of motions based on time warps of different magnitude; 2) To ensure that the discrimination is feasible only by observing and analyzing as many image frames as possible. Thus, we introduce the following transformations: forward-backward playback, random frame skipping, and uniform frame skipping.
Our experiments show that networks trained with the proposed method yield representations with improved transfer performance for action recognition on UCF101 and HMDB51.