# CSET419-Gen-AI-E23CSEU1603

Objective
The objective of this experiment is to understand the fundamentals of Generative AI by generating synthetic medical imaging data using a pre-trained generative model. Students will learn how to use Python-based tools to generate, store, and visualize synthetic X-ray samples.

Experiment 1: Implement a Simple Generative Algorithm for Medical Data Generation
Generative AI models are capable of creating new and realistic data samples based on learned patterns. In this experiment, a pre-trained generative model is used to generate synthetic X-ray images, which are then stored in a structured dataset format for further analysis, such as training diagnostic models.

Domain Selected
Medical Image Generation (Chest/Bone X-Rays)

Generative Model Used
Stable Diffusion (Pre-trained diffusion-based generative model adapted for medical imaging prompts)

Methodology / Procedure
Selected Medical X-ray Imaging as the data domain.
Loaded a pre-trained Stable Diffusion model using Python.
Provided multiple medical textual input prompts (minimum of 5) to guide the generation process (e.g., "Frontal chest X-ray of healthy lungs", "X-ray of a fractured radius bone").
Generated synthetic X-ray images using the generative model.
Saved the generated images in a folder-based dataset structure.
Displayed sample generated outputs for visual verification of anatomical structure.
Tools & Technologies
Python
Google Colab
Stable Diffusion
PyTorch
Hugging Face Diffusers Library
Output
A synthetic X-ray dataset generated using a pre-trained generative AI model.
Images stored in an organized folder structure.
Sample outputs displayed to verify data quality and anatomical realism.
Conclusion
This experiment demonstrates how Generative AI models can be used to efficiently create synthetic medical datasets. The generated data can be further utilized for tasks such as training diagnostic machine learning models, data augmentation for rare conditions, and experimentation, especially in medical scenarios where real-world patient data is privacy-sensitive or limited.
