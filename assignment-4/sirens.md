# Assignment 4

For this lab, we recommend that students read the material in the references section of this page.
This assignment aims to show the use of a SIREN in practice. In previous assignments, we worked with ReLU and LeakyReLU activation functions. In this assignment, we will work with an activation function in sinusoidal form. <a href=" https://colab.research.google.com/drive/1WFIDNwysy8ot2n_sT_V-5mHx63NhveNT#scrollTo=Z0-L0V9_EAqk" target="_blank">Click here</a> to open a simplified example of SIREN and follow the suggestions subsection instructions.

## Suggestions:

1. Create a copy of the notebook.
2. Run the cells; we recommend running them one by one to get familiar with the process.
3. The authors in the paper call attention to the adjustment of $\Omega_0$ initialization. Into the notebook are suggestions for specific sections of the paper; we recommend the students read these parts and try to adjust the $\Omega_0$ value. Afterward, the students can compare their results with the provided example and show us. 
4. Do a network initialization, but remove the $\Omega_0$ in the hidden layers. Then, write about the network behavior.
5. To verify the importance of normalization, we suggest removing init-weights and initializing the network to an arbitrary value. Then, write about the network behavior.
6. Write a review saying how we could merge gradient-domain images using SIRENs. Use the Poisson Image Editing material available in the References section. 

## Important

The deadline for submitting the assignment is 07/01/2023.

## **References**

*Mestrado: Processamento de Imagens - 2022*

[![Mestrado: Processamento de Imagens - Luiz Velho - Aula 04](https://i.ytimg.com/vi/pqVn_JE84V0/hqdefault.jpg?sqp=-oaymwE1CKgBEF5IVfKriqkDKAgBFQAAiEIYAXABwAEG8AEB-AH-BIAC6AKKAgwIABABGGUgZShlMA8=&rs=AOn4CLA8_EGFxerfGn1M8yRz01-PaYNLSQ)](https://www.youtube.com/watch?v=pqVn_JE84V0&list=PLo4jXE-LdDTSWs21bioxuqEaXcLq7NUJB&index=4)

*Papers*
SIREN, <a href=" https://arxiv.org/abs/2006.09661" target="_blank">click here</a> .

Poisson Image Editing, <a href=" https://dl.acm.org/doi/10.1145/882262.882269" target="_blank">click here</a> .
