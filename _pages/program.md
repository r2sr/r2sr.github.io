---
layout: page
permalink: /program/
title: Workshop Program
description: The program of the workshop (details will be added as the workshop date approaches).
nav: true
nav_order: 2
---

## Workshop Program

Venue information : [see here](https://r2sr.github.io/local/#workshop-venue).

**Monday, November 13, 2023**

|  Time  |   Description  |
| :---- |  :-------      |
| 9 - 9:30 AM |  Breakfast  |
| 9:30 - 10:00 AM |  Welcome + Introductions |
| 10:00 AM - 10:15 AM | Presentation by NSF   |
| 10:30 AM - 12:15  noon | Theme Setting Presentations |
| 12 - 1 PM |  Lunch |
| 1 - 1:30 PM | Organization, Meta-discussion, breakout into teams, team leader election |
| 1:30 - 3 PM | Discussion Round # 1  |
| 3 - 3:30 PM | Break |
| 3:30 - 5:00 PM | Discussion Round # 2 |
| 5 - 5:30 PM | Brief report out from discussion group leaders |
| 5:30 PM - 7:30 PM | Dinner at a local restaurant (TBA)  |

**Tuesday, November 14, 2023**

| Time  |  Description |
| :---- |  :-------      |
| 9 - 9:30 AM |  Breakfast  |
| 9:30 - 11:00 AM |  Discussions Round # 3 |
| 11 - 12:30 PM |  Report out from each discussion group. |
| 12:30 PM  | Workshop concludes |

<p/><p/>

## Theme Setting Presentations

These presentations will be 15 minutes each, focussing broadly on the challenges
of doing scientific research in a rigorous and reproducible manner, identifying
possible solutions both near term and longer term, and thinking about
opportunities for applying formal methods and related techniques.


### 10:30 AM - Natarajan Shankar (SRI)

>  Title: The Meaning of Computation
>
> Abstract: Science relies on computation on a number of counts.  Computation is
> used to collect and analyze large volumes of scientific data.  It is also used
> to run simulations of scientific laws, models, and theories.  Finally,
> computation is used as a modelling framework for scientific concepts and
> theories at different levels of abstraction.  Computational models are used both
> for analysis and synthesis.  The computation revolution in science has enabled
> us to deal with complex models and calculations that are well beyond the scope
> of human intuition.  This leaves a big gap between the long chains of
> calculation and their intuitive scientific interpretation, between the large
> volume of data and claims for the provenance and properties of the data, and
> between differing computational implementations of the same scientific content.
> We look at a few approaches toward closing some of these gaps including formal
> mathematical modeling using proof assistants, code generation from high-level
> models, data definition languages for rigorously describing data formats, ontic
> types to labeling data (at rest or in flight) with metadata, witness-producing
> computations, and the evidential tool bus for defining evidence-curating,
> reproducible workflows.
>
> Bio: Dr. Natarajan Shankar is a Distinguished Senior Scientist and SRI Fellow at
> the SRI Computer Science Laboratory.  He is the author of the book,
> "Metamathematics, Machines, and Godel's Proof", published by Cambridge
> University Press.  Dr. Shankar is the co-developer of a number of formal
> analysis technologies including the PVS interactive proof assistant, the SAL
> model checker, and the Yices SMT solver.  He is a co-recipient of the 2012 CAV
> Award and the recipient of the 2022 Herbrand Award.

### 10:45 AM - Jeremy Avigad (CMU)

> Title: Where the money is
>
> Abstract: 
> As the story goes, when a reporter asked bank robber Willie Sutton was asked why
> he robbed banks, he replied, "because that's where the money is." Formal 
> verification is difficult, and when faced with the question as to why we should 
> bother to verify a piece of software, the only reasonable answer is "because that's where the problems are."
> In this talk, I will discuss some examples of mathematical and scientific software where verification matters
> and where proof assistant technology can help ensure that the results are reliable.
>



#### 11:00 AM - Karthik Duraisamy (Michigan)

> Title: Challenges and Opportunities in Rigorous End-to-end Verification and Validation for Scientific Computing.
>
> Abstract: This talk will begin with an introduction of the different sources of errors and uncertainties in complex scientific computing applications. The second part of the talk will touch upon some recent work in formal (and less formal) reasoning in end-to-end verification and validation (V&V) of predictive models. This will be followed by a brief discussion of future possibilities in automated reasoning for V&V.





#### 11:15 AM - Jean Peccoud (Colorado State University)

> Title: What is a reproducible result? 
> 
> Abstract: A naïve understanding of reproducibility assumes that reproducible results are data with a variance of 0. Every experimental data has some experimental error and uncontrolled sources of variation. Therefore, reproducibility must be associated with a higher level of abstraction where different datasets lead to the same conclusions with a certain confidence level. In order to support this type of analysis, it is necessary to properly manage data before starting the data collection.


#### 11:30 AM - Borzoo Bonakdarpour (Michigan State University)

> Title: Identifying Casual Structures by Automated Reasoning
>
> Abstract: Scientific investigations have two purposes: (1) discovering previously unknown associations between a natural phenomenon (e.g., individuals infected with the Alzheimer’s disease (AD) often experience memory loss), and (2) generating precise mechanistic explanations for how the phenomena are causally related (e.g., a combination of genetic, lifestyle and environmental factors that affect the formation of amyloid beta and tau proteins in the brain tissue). Among these two purposes, explanation is the most critical to achieve global impact; identifying the major root-causes of natural phenomena not only enables scientists to predict their future outcomes, but also implies the means in which we prevent or mitigate such events. In this talk, I will describe a framework for formalizing the notion causality based on the definition of Actual Causality by Halpern and Pearl. I will also explain how decision procedures such as SMT solving are capable of extracting causal structures in different areas of natural and social sciences.

#### 11:45 AM - Vijay Ganesh (Georgia Tech)

> Title: Automated Scientific Discovery via Solvers and Machine Learning
> 
> Abstract: We present some initial results in discovery of physics equations via a combination of SAT/SMT solvers and symbolic regression (SR). The key idea is a corrective feedback loop between an SR tool that takes as input data and outputs equations, and an SMT solver that checks the consistency of said equations against background knowledge and provides corrective feedback to the SR tool in terms of new data points. Using our method, we have managed to learn several equations from the Feynman book on physics.




## Discussion Topics

We will have a detailed set of discussion topics to be discussed. For convenience, we have broken down the topics into overlapping discussion themes.

**Note:**  these are quite preliminary and will likely change over the next few weeks.

  - **The Scientific Research Process** Describe typical project workflow in your area at a relevant level of detail.
     - How do you (or scientists in your area) typically acquire data?
        - How do you assess data reliability.
     - How do you process data?
     - What kind of software do you use? How do you validate this software?
     - How is the data processing described in your papers? Are there community-wide standards of what is acceptable?  Are they specified somewhere?
     - What is the typical state of reproducibility of scientific findings in your area?
        - Is reproducibility valued in your community? Do members of your community take time to reproduce other people's works?
  - **Specifying, Validating and Reproducing Scientific Discoveries:** Describe what your research/related work in formal methods can do to promote reproducibility.
     - What kind of specification formalisms can we bring about?
        - What aspects of data processing do these specification formalisms address?
        - Can these specifications encode how to reach conclusions from data?
     - What is the role of modeling when it comes to scientific workflows?
     - What sort of correctness properties can be analyzed by existing techniques?
     - How do we make existing techniques more usable to scientists?
     - Are there areas where your research can make some immediate impact in terms of enhancing scientific rigor/reproducibility?
  - **Rethinking Modern Peer-Review and Publication Processes:**  How can we enhance scientific publication process in the modern age?
    - What are the peer-review standards in your area?
       - How do peer reviewers approach supplementary materials/software?
       - Is reproducibility part of the peer review process?
    - How should publication process and journals  in your area respond to the challenges of reproducing scientific research?
      - What changes would be useful?
      - Are there journals that are making these changes? (point us to examples).
  - **Further discussion topics**
    - Promising approaches that are applicable to specific scientific areas.
    

## Discussion Organization

We will describe how the discussion will be organized to allow all participants to rotate through all the discussion themes over the workshop duration. We will also designate leaders and have volunteers who will take notes during these discussions.
