---
title: "Camera model identification based on forensic traces extracted from homogeneous patches"
description: "We propose a camera model identification using ConvNets based on homogeneous patches."
tags: ["publication"]
date: "2022-11-01"
showAuthor: true
authors:
  - "guru"

  
showAuthorsBadges: true
---


> ## Highlights
> - We propose a camera model identification using ConvNets based on homogeneous patches.
> - It consists of a hierarchical (brand, model, and device) classification scheme.
> - Natural images contain sufficient homogeneous regions for forensic trace extraction.
> - We achieve 99.01% accuracy on the 18 camera models of the Dresden data set.
> - With this result, we outperform the state-of-the-art on the same data set.

## Abstract
A crucial challenge in digital image forensics is to identify the source camera model used to generate given images. This is of prime importance, especially for Law Enforcement Agencies in their investigations of Child Sexual Abuse Material found in darknets or seized storage devices.

In this work, we address this challenge by proposing a solution that is characterized by two main contributions. It relies on the extraction of rather small homogeneous regions that we extract very efficiently from the integral image, and on a hierarchical classification approach with convolutional neural networks as the underlying models. We rely on homogeneous regions as they contain camera traces that are less distorted than regions with high-level scene content. The hierarchical approach that we propose is important for scaling up and making minimal modifications when new cameras are added. Furthermore, this scheme performs better than the traditional single classifier approach. By means of thorough experimentation on the publicly available Dresden data set, we achieve an accuracy of 99.01% with 5-fold cross-validation on the ‘natural’ subset of this data set. To the best of our knowledge, this is the best result ever reported for Dresden data set.

{{< alert "lightbulb" >}}
[Read more](https://www.sciencedirect.com/science/article/pii/S0957417422010430?via%3Dihub) in the official publication.
{{< /alert >}}
