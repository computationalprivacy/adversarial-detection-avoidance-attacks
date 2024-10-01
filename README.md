# Adversarial Detection Avoidance Attacks

In this repo we provide the deduplicated version of the [Imagenet](https://www.image-net.org/challenges/LSVRC/2012/) dataset and the code for the paper [Adversarial Detection Avoidance Attacks: Evaluating the robustness of perceptual hashing-based client-side scanning](https://arxiv.org/abs/2106.09820) by Ana-Maria Cretu, Shubham Jain and Yves-Alexandre de Montjoye.

We remove the duplicated images through a semi-automated analysis of the dataset, details for which are available in our paper. We only deduplicate the Imagenet dataset that do not contain any faces. Images containing faces are extracted from the code of the paper [A Study of Face Obfuscation in ImageNet](https://github.com/princetonvisualai/imagenet-face-obfuscation/blob/main/README.md).

We also provide a dataloader to assist in the loading this dataset. The dataloader is available in the `dataloader.py` file.
