# PleuraNet: Advanced Pleural Effusion Detection via Dual-Expert Deep Learning Ensemble

## Project Description
Engineered a medical computer vision framework elevating baseline diagnostic accuracy from 95.00% to a 98.50% validation consensus. Built an automated pipeline using OpenCV CLAHE preprocessing and parallel dual-stream routing to feed two pre-trained experts: **EfficientNet-B3** for fine-grained costophrenic angle texture mapping and **ConvNeXt-Base** for macro-structural lung geometry. Integrated outputs via a 50/50 weighted probability fusion layer into a live **Streamlit** server, featuring a built-in **Clinical Variance Triage Engine** that flags ambiguous edge-cases for mandatory radiologist review whenever model disagreement crosses a 30% safety threshold.

## Repository Contents
* `Brain_1 [EfficientNet].ipynb`: Training and optimization workflow for the texture specialist backbone.
* `Brain 2 [ConvNeXt].ipynb`: Training and optimization workflow for the structural specialist backbone.
* `Streamlit_Live.ipynb` / Scripts: Front-end clinical dashboard server deployment code.
* `Internship_Project Live Demo.ipynb`: End-to-end inference verification pipeline.
