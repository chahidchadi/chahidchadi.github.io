---
ident: academic-projects
layout: page
title: My Academic Projects
description: Master's thesis on Schwarz-type Domain Decomposition Methods
lang: en
---

# Chadi Chahid - Academic Projects

## Master's Thesis: Schwarz-type Domain Decomposition Methods

**Title:** Méthodes de décomposition de domaine de type Schwarz

**Description:**  
This master's thesis explores Schwarz-type domain decomposition methods for solving complex partial differential equations (PDEs). The research focuses on improving the efficiency and accuracy of numerical solutions for large-scale problems, particularly in the context of parallel computing.

**Key Details:**
- **Degree:** Master en Analyse Numérique et Équations aux Dérivées Partielles
- **Institution:** Université Moulay Ismail
- **Supervisor:** Prof. Khallouq Samir
- **Year:** 2023

**Objectives:**
- Present a detailed development of Schwarz methods
- Understand the necessities that led to their development
- Analyze their advantages and optimal uses compared to one another

**Key Topics:**
1. Introduction to domain decomposition and associated problems
2. Historical aspect of Schwarz methods
3. Classical Schwarz method and its parallel version
4. Convergence analysis using Fourier analysis
5. Dirichlet-Neumann method for non-overlapping domains
6. Optimized Schwarz methods for both overlapping and non-overlapping cases
7. Discretization of Schwarz methods
8. Numerical simulations and interpretations

**Methodology:**
- Implementation of finite difference methods for discretization
- Adaptation of Schwarz's convergence proof for rectangular domains
- Use of Fourier analysis to calculate convergence factors
- Variational interpretation of the Schwarz method
- Matrix formulation of alternating Schwarz methods

**Key Contributions:**
- Comprehensive analysis of various Schwarz-type domain decomposition methods
- Detailed convergence proofs and factor calculations
- Comparison and optimization of different methods
- Generalization of discretization for all studied methods

**Technologies Used:**
- Numerical analysis software (e.g., MATLAB, Python with NumPy/SciPy)
- High-performance computing resources for parallel computations
- Visualization tools for result analysis and presentation

**Keywords:** 
Domain decomposition, Alternating and parallel Schwarz methods, Optimized Schwarz methods, Dirichlet-Neumann methods, Multiplicative and additive Schwarz methods
<embed src="/cv/Rapport Projet Fin d'Études.pdf" width="100%" height="600px" type="application/pdf">


<script>
    // URL of PDF document
    var url = '/cv/Rapport Projet Fin d'Études.pdf';

    // Load the PDF document
    pdfjsLib.getDocument(url).promise.then(function(pdf) {
        // Get the first page
        pdf.getPage(1).then(function(page) {
            var scale = 1.5;
            var viewport = page.getViewport({scale: scale});

            // Get canvas element
            var canvas = document.getElementById('pdf-canvas');
            var context = canvas.getContext('2d');
            canvas.height = viewport.height;
            canvas.width = viewport.width;

            // Render PDF page into canvas context
            var renderContext = {
                canvasContext: context,
                viewport: viewport
            };
            page.render(renderContext);
        });
    });
</script>

This master's thesis provides a thorough exploration of Schwarz-type domain decomposition methods, offering valuable insights into their development, analysis, and practical applications in solving complex PDEs efficiently.
## Bachelor's Final Project: Solving Differential Equations with Laplace Transforms

**Title:** Résolution des équations différentielles par la transformée de Laplace

**Description:**  
This project explores the application of Laplace transforms in solving linear differential equations with constant coefficients. The research highlights the power and versatility of this mathematical technique in various fields of applied mathematics, physics, and engineering.

**Key Details:**
- **Degree:** Licence Fonademental en Mathématiques Appliquées
- **Institution:** Université Moulay Ismail
- **Supervisor:** Prof. Mohamed Zitane
- **Year:** 2021

**Introduction:**
The Laplace Transform, alongside the Fourier Transform, is one of the most important integral transformations. It plays a crucial role in mathematical physics, probability calculus, automation, and classical analysis. Named after Pierre-Simon Laplace (1749-1827), who began his work in the 1770s, the Laplace Transform has proven invaluable in presenting functions, sequences, partial sums, and series remainders in integral form to obtain their developments.

Differential equations have recently attracted considerable attention due to their numerous applications in various fields such as physics, biology, and economics. The solution of differential equations is often complex, and analytical methods like the Laplace Transform method have become popular for determining exact solutions of linear differential equations.

**Objectives:**
- Explore the theoretical foundations of the Laplace Transform
- Demonstrate the application of Laplace Transforms in solving linear differential equations with constant coefficients
- Analyze the advantages and limitations of the Laplace Transform method

**Methodology:**
1. Transform the differential equation using the Laplace Transform
2. Solve the resulting algebraic equation
3. Apply the inverse Laplace Transform to obtain the solution

**Key Contributions:**
- Comprehensive study of Laplace Transform theory and applications
- Development of systematic approaches for solving various types of linear differential equations
- Analysis of the advantages of Laplace Transform methods in simplifying complex problems
- Practical examples demonstrating real-world applications in physics and engineering

**Technologies Used:**
- Mathematical software for symbolic computations (e.g., Mathematica, MATLAB Symbolic Math Toolbox)
- Numerical computation tools for result verification
- LaTeX for mathematical typesetting and report preparation

This project demonstrates the power of the Laplace Transform in solving differential equations, providing a strong foundation for advanced studies in applied mathematics and its applications in various scientific and engineering fields.
<embed src="/cv/Résolution des équations différentielles par la transformée de Laplace.pdf" width="100%" height="600px" type="application/pdf">


<script>
    // URL of PDF document
    var url = '/cv/Résolution des équations différentielles par la transformée de Laplace.pdf';

    // Load the PDF document
    pdfjsLib.getDocument(url).promise.then(function(pdf) {
        // Get the first page
        pdf.getPage(1).then(function(page) {
            var scale = 1.5;
            var viewport = page.getViewport({scale: scale});

            // Get canvas element
            var canvas = document.getElementById('pdf-canvas');
            var context = canvas.getContext('2d');
            canvas.height = viewport.height;
            canvas.width = viewport.width;

            // Render PDF page into canvas context
            var renderContext = {
                canvasContext: context,
                viewport: viewport
            };
            page.render(renderContext);
        });
    });
</script>
