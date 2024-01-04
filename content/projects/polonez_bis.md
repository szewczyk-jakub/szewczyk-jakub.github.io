---
title: "In search of prediction error representations"
#date: 2023-10-01
#tags: ["keyword 1","keyword 2","keyword 3"]
author: " "
description: "In search of prediction error - popular description" 
summary: "Using fMRI, I'm looking for the evidence that the brain encodes error representations in line with the prediction error theory." 
cover:
    image: "predictive_coding3.png"
    alt: "Predictive coding schematics"
    relative: false
#editPost:
#    URL: "https://youtube.com/playlist?list=PL5zEkRHvv2GxQlFbNf-YqSPMP6ePc3DQf"
#    Text: "YouTube playlist"
showToc: false
#disableAnchoredHeadings: false
weight: 1
---

This project is funded by Polonez BIS grant and is currently undergoing.  
  
I plan two fMRI studies:
1. Conceptual replication of an influential study by [Blank & Davis (2016)](https://journals.plos.org/plosbiology/article?id=10.1371/journal.pbio.1002577). This is a decoding study in which participants were presented with spoken words of varying signal quality (bottom-up information), which were preceded by written words (repetition vs no priming; top-down information). B&D reported an interactive effect, whereby the spoken word can be decoded from brain activations only when the word is easy to recognize but there is no prior information, or when there is prior information but the word is difficult to recognize. This pattern, according to B&D, is in line with decoding from prediction error units. <br/><br/>
Currently I'm replicating this study using visually presented words (to utilize the wealth of information about the ventral visual stream), an additional priming condition (semantic priming), and encoding/decoding using features from varied levels of representation (activations in convolutional neural networks + symbolic orthographic features) at various stages of processing in the ventral stream. 
<br/><br/>
This study is conducted in collaboration with Floris de Lange, Micha Heilbron, and Peter Hagoort. 
2. In this experiment, I will focus on figure/ground segregation in the early visual cortex. Here, I plan to test how top-down information about the foregrounded figure affects the representation of the figure (a word) and of the background (random geometric shapes). I'm curious if increasing top-down information will decrease the decoding of the figure, without changing the representation of the background, or will it rather leave the representation of the figure unchanged, while dampening the representation of the background?

