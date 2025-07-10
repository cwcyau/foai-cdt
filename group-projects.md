# Project Title

When are embeddings enough?

## Challenge

Many practical applications rely on fine-tuning predictors on top of pre-trained embeddings, yet a rigorous theoretical framework explaining when this approach is truly optimal compared to end-to-end learning is lacking.

## Description 

This project aims to develop a theoretical framework, potentially using tools from statistical learning theory and information theory, to understand the conditions under which using pre-trained embeddings is optimal. The students will analyse the interplay between the pre-training data distribution, the downstream task data distribution, the size of the fine-tuning dataset, and model architecture to derive bounds and conditions that guide the choice between a frozen embedding approach (y = f(e(x))) and end-to-end model training (y = f(x)).

## Skills Required

Statistical learning theory, information theory, deep learning fundamentals 

## Skills to be Developed

Theoretical analysis, generalisation theory, embedding models 

## Relevant Background Reading

1. Shachaf, G., Brutzkus, A. and Globerson, A., 2021. A theoretical analysis of fine-tuning with linear teachers. Advances in Neural Information Processing Systems, 34, pp.15382-15394.
2. Wang, T. and Isola, P., 2020, November. Understanding contrastive representation learning through alignment and uniformity on the hypersphere. In International conference on machine learning (pp. 9929-9939). PMLR.
3. Deng, Y., Hong, J., Zhou, J. and Mahdavi, M., 2024, April. On the generalization ability of unsupervised pretraining. In International Conference on Artificial Intelligence and Statistics (pp. 4519-4527). PMLR.

Title: When does equivariance help?
Group Project: Yes
Difficulty: 8/10; 
Challenge: While theoretically appealing, there is an ongoing debate and a lack of clear quantitative understanding of the performance trade-offs associated with enforcing equivariance in neural networks versus allowing them to learn symmetries from data.
Description: This project will develop a mathematical and empirical framework to quantify the sample complexity and performance benefits of equivariant models. The student will investigate how factors like dataset size, the complexity of the symmetry group, and the use of data augmentation affect the performance gap between equivariant and standard architectures. The goal is to provide a clear understanding of when explicit equivariance provides a significant advantage, and when standard models can effectively learn the necessary symmetries from data alone.
Potential Supervisors: Andrea Vedaldi, Yarin Gal, Charlotte Deane, Michael Bronstein 
Skills Required: Group theory, Statistical learning theory, information theory, deep learning fundamentals 
Skills to be Developed: Equivariant neural networks, empirical benchmarking 
Relevant Background Reading:
	E(n) Equivariant Graph Neural Networks
	https://arxiv.org/abs/2104.13478
	AlphaFold3 (example where equivariance was removed without drop in performance)
	Azizian, W. and Lelarge, M., 2020. Expressive power of invariant and equivariant graph neural networks. arXiv preprint arXiv:2006.15646.

Title: Accelerated sampling from Boltzmann distributions with diffusion and flows models
Group Project: Both
Difficulty: 9/10; 
Challenge: Sampling from complex energy landscapes (Boltzmann distributions) is a fundamental challenge in science and ML. Traditional methods like MCMC are often slow to converge, struggle at large scale, and ML-based solutions may lack guarantees of correctness.
Description: This project will explore the use of generative models, specifically normalizing flows and diffusion models, to accelerate high-fidelity sampling from complex Boltzmann distributions. The research will focus on developing and evaluating techniques to overcome the limitations of traditional MCMC methods, aiming for efficient sampling at scale while ensuring high precision. Students will apply these methods to challenging problems in computational chemistry and physics, such as sampling molecular conformations or spin-glass configurations, and benchmark their accuracy in estimating key statistical properties (e.g., moments, free energies).
Potential Supervisors: Ard Louis, Yee Whye Teh, Coralia Cartis
Skills Required: Probabilistic modelling, MCMC, normalising flows, diffusion models 
Skills to be Developed: Generative models, advanced sampling methods 
Relevant Background Reading:
	https://arxiv.org/abs/2506.16471
	https://arxiv.org/abs/2201.13117
	https://journals.aps.org/prl/abstract/10.1103/PhysRevLett.125.121601
	Midgley, L.I., Stimper, V., Simm, G.N., Schölkopf, B. and Hernández-Lobato, J.M., 2022. Flow annealed importance sampling bootstrap. arXiv preprint arXiv:2208.01893.
	Cabezas, A., Sharrock, L. and Nemeth, C., 2024. Markovian Flow Matching: Accelerating MCMC with Continuous Normalizing Flows. arXiv preprint arXiv:2405.14392.

Title: Multiscale Foundation Models
Group Project: Yes
Difficulty: 8/10; 
Challenge: Many domains (genes in DNA, chapters in books) exhibit long-scale hierarchical dependencies that are poorly captured by existing autoregressive foundational models.
Description: Develop and evaluate hierarchical or multiscale masked autoencoder (MAE) architectures for learning rich representations from large biomolecular datasets (e.g., genomics, proteomics), focusing on capturing long-range dependencies and functional motifs.
Potential Supervisors: Charlotte Deane, Stephen Roberts, Tom Rainforth 
Skills Required: Deep learning, sequence modelling, MAEs 
Skills to be Developed: Multiscale model design, application to biological data 
Relevant Background Reading: 
	Diffusion-LM
	Structured Denoising Diffusion Models in Discrete State-Spaces
	Latent Diffusion Model for DNA Sequence Generation
	https://arxiv.org/abs/2111.06377
Title: Autonomous Lab Agent for Experimental Design
Group Project: Yes
Difficulty: 7/10
Note: This is a more focused version of the project “AI Scientists and Reinforcement Learning”.
Description:
Design and evaluate a reinforcement learning (RL) or planning-based agent capable of optimizing experimental decisions in a simulated laboratory environment. The goal is to emulate aspects of autonomous scientific discovery by developing an agent that selects actions (e.g., experimental conditions or measurement sequences) to maximize information gain or target outcome efficiency. The project will focus on proof-of-concept systems, such as toy models of chemical or biological processes, where the agent learns optimal strategies for experiment design.
Potential Supervisors: Ingmar Posner, Mike Osborne, Jakob Foerster
Skills Required:
	Reinforcement learning fundamentals
	Basic probability and decision theory
	Familiarity with OpenAI Gym or similar simulation environments
Skills to be Developed:
	Experimental design and active learning
	Policy learning and model-based RL
	Integration of physical process knowledge into AI systems
	Reproducible simulation pipelines for scientific domains
Relevant Background Reading:
	[Gómez-Bombarelli et al., 2018] Automatic Chemical Design Using a Data-Driven Continuous Representation of Molecules
	[Schneider et al., 2020] Autonomous Experimentation Systems for Materials Development: A Community Perspective
Title: Causal Integration in Foundation Models for Mechanistic Understanding
Group Project: Yes
Difficulty: 7/10; 
Challenge: Despite their enormous popularity, the mechanisms that LLMs use to perform tasks and the related failure modes are poorly understood.
Description: Research methods for incorporating causal knowledge or discovering learnt causal structure within large language models (LLMs) and diffusion models, aiming to improve our understanding of these models, generate mechanistic hypotheses and seamless integration of observational and interventional data during training and inference.
Potential Supervisors: Patrick Rebeschini, François Caron, Chris Holmes 
Skills Required: Causality, LLMs, machine learning theory 
Skills to be Developed: Causal inference, representation learning 
Relevant Background Reading: 
	https://openreview.net/pdf?id=Idusfje4-Wq,
	https://arxiv.org/abs/2412.12095 ,
	https://arxiv.org/abs/2310.20307
Title: Calibrated Uncertainty Estimation in LLMs and Diffusion Models
Group Project: Yes
Difficulty: 6/10; 
Challenge: Standard foundation models often produce confident but incorrect predictions, limiting their reliability for high-stakes scientific and medical applications.
Description: Investigate and implement state-of-the-art uncertainty quantification techniques (e.g., conformal prediction, Bayesian deep learning, ensembles) for large language models and diffusion models. The project will focus on developing methods to produce well-calibrated confidence intervals and reliable uncertainty estimates for outputs in both BioFM and PatientJourneyFM contexts, enhancing model trustworthiness.
Potential Supervisors: Yee Whye Teh, Yarin Gal, Stephen Roberts, Chris Holmes
Skills Required: Bayesian methods, conformal prediction, calibration techniques 
Skills to be Developed: Uncertainty estimation, trustworthy AI 
Relevant Background Reading: TBD

