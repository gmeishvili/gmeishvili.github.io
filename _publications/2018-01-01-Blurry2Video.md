---
title: "Learning to Extract a Video Sequence from a Single Motion-Blurred Image"
collection: publications
permalink: /publication/2018-01-01-Blurry2Video
date: 2018-01-01
venue: 'IEEE Conference on Computer Vision and Pattern Recognition (Spotlight)'
citation: 'J. Meiguang, G. Meishvili, and P. Favaro (2018). &quot;Learning to Extract a Video Sequence from a Single Motion-Blurred Image	.&quot; <i>CVPR 2018</i>.'
---

 [[PDF]](https://openaccess.thecvf.com/content_cvpr_2018/papers/Jin_Learning_to_Extract_CVPR_2018_paper.pdf) [[Project Page]]() [[Code]](https://github.com/MeiguangJin/Learning-to-Extract-a-Video-Sequence-from-a-Single-Motion-Blurred-Image) 

## Abstract

We present a method to extract a video sequence from a single motion-blurred image. Motion-blurred images are the result of an averaging process, where instant frames are accumulated over time during the exposure of the sensor. Unfortunately, reversing this process is nontrivial. Firstly, averaging destroys the temporal ordering of the frames. Secondly, the recovery of a single frame is a blind deconvolution task, which is highly ill-posed. We present a deep learning scheme that gradually reconstructs a temporal ordering by sequentially extracting pairs of frames. Our main contribution is to introduce loss functions invariant to the temporal order. This lets a neural network choose during training what frame to output among the possible combinations. We also address the ill-posedness of deblurring by designing a network with a large receptive field and implemented via resampling to achieve a higher computational efficiency. Our proposed method can successfully retrieve sharp image sequences from a single motion blurred image and can generalize well on synthetic and real datasets captured with different cameras.