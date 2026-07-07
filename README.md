# EO-to-SAR Prototype Alignment

> **Under construction:** this repository is being prepared for release.

This repository contains the code for the SPIE conference paper *Cross-Modal
Knowledge Transfer for SAR Target Recognition Using Optical Vision Foundation
Models*. 

The project studies how electro-optical (EO) vision foundation models
can provide class level prototype references for Synthetic Aperture Radar (SAR)
target recognition. A frozen EO DINOv3 encoder is used to construct optical
class prototypes, while a SAR encoder (fine tuned with LoRA) is trained to classify SAR
images and align its embeddings to the corresponding EO prototypes. At inference
time, the model uses only SAR imagery.
