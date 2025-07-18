# Visual Reasoning with Diffusion Models

## Challenge

While language models have made significant strides in textual reasoning, complex visual reasoning, analogous to question-answering but in the pixel space, remains a frontier. Most models can classify or segment, but struggle with compositional or counterfactual visual tasks.

## Description

This project will explore the use of conditional diffusion models as a backbone for visual reasoning. The goal is to move beyond static tasks and develop models that can answer "what if" questions about visual scenes. For example, given an image, the model could be prompted to perform tasks like: "show me this scene if the car were red," "realistically remove this object," or "predict the shadow's position if the light source moved." This involves designing novel visual reasoning benchmarks and developing architectures that can interpret multimodal prompts (e.g., text + masks) to perform complex, compositional image edits that demonstrate a form of visual understanding.

## Skills Required 

Strong proficiency in Python and PyTorch/JAX, good understanding of deep learning fundamentals, experience with generative models (diffusion models are a plus).

## Skills to be Developed

Advanced generative modeling, multimodal fusion architectures, novel benchmark design for AI, conditional image generation, and evaluating abstract reasoning capabilities in vision models.

## Relevant Background Reading

1. Rombach, R., Blattmann, A., Lorenz, D., Esser, P. and Ommer, B., 2022. High-resolution image synthesis with latent diffusion models. In Proceedings of the IEEE/CVF conference on computer vision and pattern recognition (pp. 10684-10695).
2. Brooks, T., Holynski, A. and Efros, A.A., 2023. Instructpix2pix: Learning to follow image editing instructions. In Proceedings of the IEEE/CVF conference on computer vision and pattern recognition (pp. 18392-18402).
3.	Wewer, C., Pogodzinski, B., Schiele, B. and Lenssen, J.E., 2025. Spatial reasoning with denoising models. arXiv preprint arXiv:2502.21075.
4.	Stanić, A., Caelles, S. and Tschannen, M., 2024. Towards truly zero-shot compositional visual reasoning with llms as programmers. arXiv preprint arXiv:2401.01974.
