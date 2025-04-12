# Geometric Analysis of Reasoning Trajectories: A Phase Space Approach to Understanding Valid and Invalid Multi-Hop Reasoning in LLMs

## Overview
This repository contains the research paper and accompanying code for the study "Geometric Analysis of Reasoning Trajectories: A Phase Space Approach to Understanding Valid and Invalid Multi-Hop Reasoning in LLMs" by Javier Marín. The project introduces an innovative framework that applies principles from Hamiltonian mechanics and differential geometry to analyze and optimize reasoning processes in AI systems, particularly focusing on multi-hop question answering tasks.

## Contents
Paper folder: The full research paper detailing the theoretical framework, methodology, results, and discussions.
Hamiltonian_final_version.ipynb: Jupyter notebook containing the implementation of experiments, data analysis, and visualizations described in the paper.

## Abstract
This paper proposes a novel approach to analyzing multi-hop reasoning in language
models through Hamiltonian mechanics. We map reasoning chains in embedding spaces
to Hamiltonian systems, defining a function that balances reasoning progression (kinetic
energy) against question relevance (potential energy). Analyzing reasoning chains from
a question-answering dataset reveals that valid reasoning shows lower Hamiltonian
energy values, representing an optimal trade-off between information gathering and
targeted answering. While our framework offers complex visualization and quantification
methods, the claimed ability to ”steer” or ”improve” reasoning algorithms requires more
rigorous empirical validation, as the connection between physical systems and reasoning
remains largely metaphorical. Nevertheless, our analysis reveals consistent geometric
patterns distinguishing valid reasoning, suggesting this physics-inspired approach offers
promising diagnostic tools and new perspectives on reasoning processes in large language
models

## Key Features
Application of Hamiltonian mechanics to AI reasoning processes
Analysis of reasoning trajectories using differential geometry
Implementation of conservation laws and canonical transformations in cognitive spaces
Comprehensive statistical analysis and visualization of reasoning patterns
Novel metrics for evaluating the quality and efficiency of AI reasoning

## Requirements

For a full list of dependencies and their versions, please refer to the requirements.txt file.
Usage

## Clone this repository:
Copygit clone [https://github.com/Javihaus/Optimizing-AI-Reasoning]

## Install the required dependencies:
Copypip install -r requirements.txt

## Dataset
This project uses the OpenBookQA (OBQA) dataset. We used the OpenBookQA (OBQA) dataset for our research, which provides a standard to assess the question answering and reasoning abilities of AI systems. The OBQA dataset was presented by Mihaylov et al. (2018) in their research on open-book question answering.
- Mihaylov, T., Clark, P., Khot, T., & Sabharwal, A. (2018). Can a suit of armor conduct electricity? a new dataset for open book question answering. Ar Xiv PreprintArXiv:1809.02789.

## Results
The main findings of this study include:

Valid reasoning chains exhibit lower and more stable Hamiltonian energy profiles compared to invalid chains.
Trajectory curvature and conservation of angular momentum-like quantities are effective discriminators of reasoning validity.
The framework reveals potential fundamental principles governing effective cognitive processes in AI systems.

For detailed results and discussions, please refer to the full paper.

## Citation
If you use this work in your research, please cite:
Marín, J. (2024). Geometric Analysis of Reasoning Trajectories: A Phase Space Approach to Understanding Valid and Invalid Multi-Hop Reasoning in LLMs. arXiv preprint arXiv:2410.04415v3
(DOI:10.48550/arXiv.2410.04415)


## License
This project is licensed under the MIT License - see the LICENSE file for details.

## Contact
For any questions or feedback, please contact Javier Marín at javier@jmarin.info.
