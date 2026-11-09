# FLUX-OD

FLUX-OD studies synthetic-data augmentation for object detection in low-data settings. The work is motivated in part by the gEICko robotic capture project, where collecting real imagery of uncooperative orbital objects is difficult. The experiments use six object-detection datasets to investigate the augmentation problem; they do not evaluate orbital imagery directly.

## Project

The pipeline uses FLUX.1-Fill with class-specific LoRA adaptation to generate object-level image edits. It evaluates generation planning and post-generation filtering as separate choices, and measures their effects by training a downstream YOLOv7 detector. The experiments examine how outcomes vary with allocation strategy, synthetic-data quantity, and dataset. Image-quality metrics are also compared with detector performance; they are treated as diagnostics, not assumed predictors of training utility.

The central question is whether generated samples add useful training information beyond a small labelled real-data set, and under which conditions. Synthetic images are not assumed to improve detection simply because they look plausible or because more are added.

## Repository Status

This repository is currently a project placeholder. Source code, configuration files, and the resources and instructions needed to reproduce the experiments will be added soon. No experimental code or datasets are included yet.
