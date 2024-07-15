---
title: Program
nav: true
---

# Program of the workshop

Unless specified explicitly, the location is SAS 2203 (in particular, all the talks will take place there).

## Saturday July 20

9:00-10:00: Breakfast and Coffee (SAS Lobby)
<br>
<br>

10:00-10:40: Nicolette Meshkat, *Identifiability and indistinguishability of linear compartmental models*
<details><summary>Abstract</summary>
An important question that arises when modeling is if the unknown parameters can be determined from data, the parameter estimation problem.  A key first step is to ask which parameters can be determined given perfect data.  This is called the structural identifiability problem.  We examine this question for a class of models called linear compartmental models, used in pharmacokinetics, physiology, cell biology, toxicology, and ecology.  We also examine a related problem called indistinguishability, which examines if two distinct models yield the same dynamics.  We will consider the underlying graph corresponding to our model and use tools from graph theory and computational algebra to analyze our models.
</details>
<br>

10:40-11:20: Cash Bortner, *Identifiability of linear compartmental models*
<details><summary>Abstract</summary>
Recovering parameter values from mathematical models is a primary interest of those who use them to model the physical and biological world. This recovery, or identification, of parameters within models is also an interesting mathematical problem that we call Identifiability. In this talk, we will explore the identifiability of a specific type of model called Linear Compartmental Models, which are often used to understand biological phenomena and have an underlying graphical structure. Specifically, we will explore the relationship between this graphical structure of Linear Compartmental Models and the corresponding model identifiability.
</details>
<br>

11:20 - 12:00: Andrew Brouwer, *Identifiability and model reduction of pharmacokinetic models of carbon stable isotope breath tests*
<details><summary>Abstract</summary>
This talk will present a simple but meaningful example of the importance and application of identifiability analysis to compartmental models in a real-world context. Carbon stable isotope breath tests provide a dose of non-radioactive 13C-labeled substrate, which is digested, absorbed, and metabolized, appearing on the breath as 13CO2. These tests offer new opportunities to better understand gastrointestinal function in health and disease. However, it is often not clear how to isolate information about a gastrointestinal or metabolic process of interest from a breath test curve, and it is generally unknown how well summary statistics from empirical curve fitting correlate with underlying biological rates. We developed a framework that can be used to make mechanistic inference about the metabolic rates underlying a 13C breath test curve, and we applied it to a pilot study of 13C-sucrose breath test in 20 healthy adults. Starting from a standard conceptual model of sucrose metabolism, we determined the structural and practical identifiability of the model, using algebraic methods and profile likelihoods, respectively. We used these results to develop a reduced, identifiable model as a function of a gamma-distributed process; an exponential process; and a scaling term related to the fraction of the substrate that is exhaled as opposed to sequestered or excreted through urine. Our work develops a better understanding of how the underlying biological processes impact different aspects of 13C breath test curves, enhancing the clinical and research potential of these 13C breath tests.
</details>
<br>

12:00 - 1:20: Lunch (SAS 4104)
<br>
<br>

1:20 - 2:00: Helen Moore, *Identifiability within an evaluation framework for systems models*
<details><summary>Abstract</summary>
I will discuss model evaluation for quantitative systems pharmacology (QSP) models. I will include both structural and practical identifiability in the context of in-host QSP models, and my views on where identifiability should sit within a modeling workflow. I will show an example of model evaluation applied to a QSP model for multiple myeloma.
</details>
<br>

2:00 - 2:40: Zack Kenz, *Virtual population generation in quantitative systems pharmacology models with inflammation and fibrosis*
<details><summary>Abstract</summary>
Mechanistic, mathematical modeling approaches such as quantitative systems pharmacology (QSP) can identify the links between pathophysiologic mechanisms and clinical sequela, aid in interpreting drug treatment results, and predict potential efficacy for novel treatments. Virtual patients, mathematically explicit hypothesis of disease pathophysiology, are generated and validated during model development and subsequently used to support decision-making (e.g., dose selection, efficacy/safety) and hypothesis testing (e.g., interrogate treatment mechanism of action, identify data gaps). Multiple methods for generation and validation of virtual populations exist; a subset will be discussed in the context of clinically relevant complex multi-scale QSP models with inflammation and fibrosis.
</details>
<br>

2:40 - 3:20: François Fages, *On modeling dynamical systems with reaction systems and their hierarchy of semantics*
<details><summary>Abstract</summary>
Historically, Chemical Reaction Networks (CRN) have been introduced to model high-level cell processes in terms of their low-level molecular interactions. Formally, a CRN, better called a Reaction System (RS), is a finite set of formal kinetic reaction rules with a well-defined hypergraph structure and several possible dynamics. One same RS model can be interpreted in a hierarchy of formal semantics related by either approximation or abstraction relationships, including the differential semantics (ordinary differential equation), stochastic semantics (continuous-time Markov chain), probabilistic semantics (probabilistic Petri net forgetting about continuous time), discrete semantics (Petri net forgetting about transition probabilities), and Boolean semantics forgetting precise numbers. We shall show how these different semantics come with different analysis tools which can reveal various dynamical properties of the other interpretations. In our CRN modeling software <a href="http://contraintes.inria.fr/biocham/">BIOCHAM</a> (biochemical abstract machine), these static analysis tools are complemented by dynamical analysis tools for parameter search based on quantitative temporal logic, and by an original CRN synthesis tool for compiling real functions in abstract elementary CRNs that can be compared with natural CRNs.
</details>
<br>

3:20 - 4:00: Coffee (SAS Lobby)
<br>
<br>

4:00 - 4:45: Problem session
<br>
<br>

5:00 - 7:00: Dinner reception (SAS 4104)
<br>
<br>
<br>

## Sunday July 21

9:00-10:00: Breakfast and Coffee (SAS Lobby)
<br>
<br>

10:00-10:40: Gerardo Chowell-Puente, *Structural and practical identifiability analysis of epidemic models based on differential equations*
<details><summary>Abstract</summary>
The successful application of epidemic models hinges on reliably estimating model parameters from limited observations. A crucial step before parameter estimation is ensuring that model parameters are structurally identifiable from observed system states. We describe a workflow for conducting structural and practical identifiability analysis of differential equation epidemic models using computational tools. Through various examples, we demonstrate that structural identifiability issues can be resolved by incorporating additional observations, assuming known initial conditions, using prior information to fix certain parameters, or modifying the model based on identified parameter correlations. We also highlight how structural identifiability analysis enriches compartmental diagrams by indicating observed state variables and analysis results.
</details>
<br>

10:40 - 11:20: Alexander Demin, *Computing globally identifiable parametrizations of dynamical models*
<details><summary>Abstract</summary>
Dynamical models described by ordinary differential equations (ODEs) are ubiquitous in engineering and the sciences. Structural identifiability is a property of a dynamical model that determines if the model parameters and states can be identified from experimental data in the absence of noise. A priori structural identifiability analysis is crucial for meaningful parameter estimation in practice. In this talk, we will present an algorithm for finding a globally identifiable parametrization of a model described by a system of ODEs, where each state and parameter in the new parametrization is directly related to the original states and parameters. Additionally, we will show how the algorithm is integrated in the form of a practical implementation in the Julia package <a href="https://github.com/SciML/StructuralIdentifiability.jl">StructuralIdentiafiability.jl</a>.
<br>
This work is a joint result by Alexander Demin, Gleb Pogudin, and Chris Rackauckas.
</details>
<br>

11:20 - 12:00: Louis Roussel, *Parameter estimation with integral elimination*
<details><summary>Abstract</summary>
In this talk, we investigate the interest of using nonlinear integral equations instead of nonlinear differential equations in a modeling context.  In particular, we compare the quality of parameter estimation on an academic example using different input-output differential and integral equations. Finally, I will present the package IntegralElimination on two examples. The Python implementation is available <a href="https://codeberg.org/louis-roussel/IntegralElimination">here</a>.
<br>
Keywords: parameter estimation, input-output equations, integral elimination
</details>
<br>

12:00 - 1:30: Lunch (SAS 4104)
<br>
<br>

1:30 - 2:10: Shaoshi Chen, *Stability problems in symbolic summation*
<details><summary>Abstract</summary>
This talk aims to initialize a dynamical aspect of symbolic summation by studying stability problems in difference fields.
We present some basic properties of stable elements in a difference field and P-recursive sequences that enable us to characterize all possible stable hypergeometric sequences. Some problems for future studies are proposed towards deeper dynamical studies in difference algebra.
</details>
<br>

2:10 - 3:00: Mentoring
<br>
<br>

3:00 - 3:30: Coffee (SAS Lobby)
<br>
<br>

3:30 - 4:10: Antonio Jiménez-Pastor, *Almost commuting bases of generic linear differential operators*
<details><summary>Abstract</summary>
The study of the centralizer of linear differential operators is useful in several applications. However, computing these objects is a challenging problem in general. In this talk, we will study almost commuting operators, which are easier to handle. These almost commuting operators form a vector space for which we can effectively compute a basis in the generic case. We will show how this algorithm works, the tools used for it and how this can help to compute non-trivial elements of the centralizer for specific linear differential operators. This is a joint work with Sonia L. Rueda.
</details>
<br>

4:10 - 4:50: Alexander Leguizamon-Robayo, *Minimization of dynamical systems over monoids*
<details><summary>Abstract</summary>
Quantitative notions of bisimulation are well-known tools for the minimization of dynamical models such as Markov chains and ordinary differential equations (ODEs). In forward bisimulations, each state in the quotient model represents an equivalence class and the dynamical evolution gives the overall sum of its members in the original model. We introduce generalized forward bisimulation (GFB) for dynamical systems over commutative monoids and develop a partition refinement algorithm to compute the coarsest one. When the monoid is (R,+), we recover probabilistic bisimulation for Markov chains and more recent forward bisimulations for nonlinear ODEs. Using (R,⋅) we get nonlinear reductions for discrete-time dynamical systems and ODEs where each variable in the quotient model represents the product of original variables in the equivalence class. When the domain is a finite set such as the Booleans, we can apply GFB to Boolean networks (BN), a widely used dynamical model in computational biology. Using a prototype implementation of our minimization algorithm for GFB, we find disjunction- and conjunction-preserving reductions on 60 BN from two well-known repositories, and demonstrate the obtained analysis speed-ups. We also provide the biological interpretation of the reduction obtained for two selected BN, and we show how GFB enables the analysis of a large one that could not be analyzed otherwise. Using a randomized version of our algorithm we find product-preserving (therefore non-linear) reductions on 21 dynamical weighted networks from the literature that could not be handled by the exact algorithm.
<br>
Joint work with Georgios Argyris, Alberto Lluch Lafuente, Mirco Tribastone, Max Tschaikowski, Andrea Vandin.
</details>
<br>
<br>

## Monday July 22

9:00-10:00: Breakfast and Coffee (SAS Lobby)
<br>
<br>

10:00-10:40: Maria Pia Saccomani, *Showcase of the software DAISY by testing identifiability examples and discussion of open problems*
<details><summary>Abstract</summary>
Complex nonlinear ordinary differential equations (ODE) models are often being proposed for modeling dynamic biological systems. The recovery of the model parameter values can be approached as a parameter estimation problem starting from input-output experiments, which is often difficult due to practical limitations and/or mathematical ill-posedness. The first relevant question is whether the model parameters can be (uniquely) determined, at least for suitable input functions. To check this property, called <em>(global) identifiability</em>, is a first step necessary to correctly solve the parameter estimation from the experimental data. Checking global identifiability is challenging and different algorithms have been proposed based on different mathematical settings.
<br>
In this context, the aims of this talk are twofold: 
<ol>
<li>
to present a new version of the software package DAISY (Differential Algebra Identifiability of SYstems), freely available from the <a href="https://daisy.dei.unipd.it">website</a>. Daisy is coded in the symbolic language Reduce and, so far, works both under Windows and MacOS. Knowledge of high-level programming languages and mathematics are not a prerequisite for using the software. This program implements complex differential and computer algebra algorithms to test the structural identifiability of dynamic systems described by polynomial (or rational) equations.  A differential algebra method is used to compute the characteristic set of the differential ideal generated by the polynomials defining the system. It implements the pseudodivision algorithm of differential polynomials proposed by Ritt and uses the Gröbner bases algorithm to solve the resulting algebraic polynomial equations. 
I will show in detail how to implement each part of the algorithm by running some examples. In particular, new improvements introduced to guarantee the theoretical correctness of the implementation (sometimes at the expense of computational complexity) will be highlighted. I will outline the peculiarities of its application to dynamical models, especially regarding the use of known initial conditions, whenever present. This requires the simulation of the input and output variables and the calculation of high order derivatives. Moreover, I will suggest some strategies and tricks, based on theoretical considerations, to increase the performance of the algorithm and the efficiency of the software. Finally, a further feature of DAISY, holding for locally identifiable models will be shown. DAISY is useful not only <em>a priori</em> (before designing an experiment), but also after numerical estimation of the parameters, as it can be used to calculate all the equivalent solutions of the model parameters, a result of crucial importance in biomedical studies.
To explain all these points, I will use real biological models recently proposed in literature through a step-by-step analysis of the algorithm.
</li>
<li>
    To discuss some open problems regarding the applicability and the efficiency of DAISY. Among these:
    <ul>
        <li>the reasons why DAISY may not terminate for specific model structures and some possible suggested solutions,</li>
        <li>the crucial step of moving from the symbolic calculation of the Gröbner bases, which in practice could be unfeasible, to a numerical one. This requires the adoption of more sophisticated randomization algorithms,</li>
        <li>the need of a user-friendly interface where one can immediately appreciate all the provided results,</li>
        <li>in addition to the global identifiability of the model, DAISY easily checks the model algebraic observability. It may also be interesting to couple DAISY to algorithms checking other important structural properties such as controllability and input persistent excitability, necessary to guarantee the correctness of the identifiability results.</li>
    </ul>
    To show all the above points I will run some classical benchmark models used for identifiability software comparison in DAISY.
</li>
</ol>
</details>
<br>

10:40-11:20: Mark Transtrum, *Extending the Manifold Boundary Approximation Method to reduce large-scale, multi-parameter models*
<details><summary>Abstract</summary>
The Manifold Boundary Approximation Method (MBAM) is a model reduction technique based on information geometry and sloppy model analysis.  This approach interprets a multi-parameter model as a manifold with parameters as coordinates.  The Fisher Information Matrix is a natural metric on this manifold, so that distance is statistical distinguishability from data.  Multi-parameter models often exhibit a systematic compression of the parameter space in the information metric, so the model manifold is very narrow in most directions, a phenomenon known as sloppiness.  We empirically observe that the boundaries of these manifolds are physically interpretable, reduced-order models.  MBAM identifies reduced-order models using geodesics to connect a complicated model to a simpler one on the boundary.  This approach is computationally and manually intensive, limiting it to moderately-sized models with a few dozen parameters.  I present a computationally efficient generalization of MBAM, applicable to models with many more parameters.  After reparameterizing, I recast the model reduction problem as a sequence of convex optimizations that can be solved efficiently for high-dimensional parameter spaces.  I demonstrate on models from physics, biology, and power systems.
</details>
<br>

11:20-12:00: Richard Allen, *Virtual Populations: Philosophy, Methods, and Opportunities*
<details><summary>Abstract</summary>
Virtual Populations are used in Quantitative Systems Pharmacologyn (QSP) models to capture parameter uncertainty and population variability. Conceptually, they are one way in which we practically overcome challenges with parameter unidentifiability. In this talk I will introduce the virtual population concept and why it is useful with real examples from drug development.
</details>
<br>

12:00-1:30: Lunch (SAS 4104)
