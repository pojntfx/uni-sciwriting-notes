% Uni Scientific Writing Notes
% Felicitas Pojtinger
% \today
\tableofcontents
\newpage

# Uni Scientific Writing Notes

## Introduction

### Contributing

These study materials are heavily based on [professor Charzinski's "Anleitung zum wissenschaftlichen Arbeiten" lecture at HdM Stuttgart](https://www.hdm-stuttgart.de/vorlesung_detail?vorlid=5212596).

**Found an error or have a suggestion?** Please open an issue on GitHub ([github.com/pojntfx/uni-sciwriting-notes](https://github.com/pojntfx/uni-sciwriting-notes)):

![QR code to source repository](./static/qr.png){ width=150px }

If you like the study materials, a GitHub star is always appreciated :)

### License

![AGPL-3.0 license badge](https://www.gnu.org/graphics/agplv3-155x51.png){ width=128px }

Uni Scientific Writing Notes (c) 2021 Felicitas Pojtinger and contributors

SPDX-License-Identifier: AGPL-3.0
\newpage

## Organization

- Primarily based on the inverted classroom principle
- Sent files should not contain metadata on person-specific info (make pseudonymous)
- Paper must be sent in by 2022-01-09
- Notes must be sent in by 2022-02-27
- Paper may be in German or English

## Overview

1. What is the scientific method?
2. Formulating scientific questions
3. Designing experiments
4. Analyzing experiments
5. Planing scientific papers
6. Researching topics and staying up-to-date
   1. Finding papers → Sci-Hub
   2. Analyzing papers
   3. Referencing papers
7. Writing a scientific paper

## What is the Scientific Method?

### Writing Style

- Structure should not follow the timeline research, but the semantic structure of the discovery
- No rhetorical questions
- No judgmental formulations
- Sentences should be able to stand on their own; reference people and things by their name, not implicit references
- Do not use the present tense when referring to past events, even if it is popular in journalism
- Do not use metaphors which are highly imprecise, even if they are common among technical people
- "I" should not be used in texts
- Summaries should be about the effect of the research on the subject, not the author's view on the subject
- The "motivation" at the start of the paper should not be the personal factors, but prior pointers

### Typical Criteria

- Complexity of the theme
- Amount of personal research
- Quality of the content
- Depth of research
- Selection of sources
- Implementation of prior knowledge
- Structure of the paper
- Visual style (used fonts, formatting etc.)
- Quote style (standardized quotes)

## Formulating Scientific Questions

### Logic and Conclusion

- Argumentation
- Logical conclusions
- Proofs (i.e. mathematical proofs)
- Experiments and their design, execution and analysis
- New analysis is always based on existing knowledge
- There are different levels of formalism: Argumentation, validation, predicate-based proofs
- Referencing ideas can be done in an "informal" way (whitepapers etc.), but they must not be the base of any claims!

### The Purpose of Writing

- Communication is the primary purpose of scientific writing
- But scientific writing is also a means of analysis
  - Formulating thesis helps to grasp the connections between arguments
  - Clear formulation makes it much harder to avoid critical questions
  - Gaps in analysis and open questions become obvious and lead to new research opportunities
  - Writing leads to a deeper internal understanding
- Even if scientific writing is limited to Uni, research methods are always required

### The Scientific Thought Model

1. Outlook
2. Own research
   1. Discussion
   2. Proofs, research, experiments, studies
   3. Hypothesis, underlying idea
3. Summary of the current state of research/technology ("related work")
4. Sources (own and external)

### Quality Assurance

- New ideas should be able to be based on existing works
- Peer reviews try to check the quality of scientific works and ensures that existing work can serve as a solid base
- Own share of own work must be made obvious

### Scientific Questions

- Formulation a concrete question is required in order to reduce the scope of topics
- The question doesn't have to be clear in the beginning of the writing process, but must be at the end
- The focus is always on the question, not the means: "Does the raft algorithm work reliably?" for example would not include/require an implementation of the raft algorithm, so always make the implementation a requirement of the question!
- The scientific question is not the title of the paper
- Just like the goals of the research need to be clearly defined, the "non-goals" need to be too!

### Experiments

- Gathering of data
- Hypothesis
  - Creating the hypothesis
  - Designing the experiment
  - Executing the experiment
  - Testing the hypothesis with the result
  - Further, refined hypothesis ideas
- The hypothesis is often "my idea/solution/architecture works"
  - Experiments support the hypothesis
  - Paper then describes the current technological state, experiments and results
- All dependencies and state required to reproduce the experiment must be notes

### Methods of Experiments

1. Design
   1. Matches the scientific question
   2. Creativity is required
   3. Viability in time, budget and with available technology
2. Planning
   1. Prevention of side effects
   2. No convenience samples
   3. No unethical experiments
3. Execution
   1. With proper process
   2. Proper documentation, including all unexpected incidents
4. Analysis
   1. Objective analysis
   2. No suppression of "unwanted" results
5. Interpretation
   1. Objective interpretation
   2. Usage of statistics: Is the result even statistically relevant?
   3. Testing the feedback loop: Has the research question actually been answered?
6. Description: Include all information required to reproduce the experiment
7. Archiving: Storage of raw data and analysis ("data can only be preserved if it massively replicated!")

### Hypothesis

- Verification using proofs
- Validation based on empirical data
- Multiple supporting hypothesis can build a theory

### Experiment Design

- Experiments should produce a result
- Testing in a specific set of parameters
  - Searching for optimal parameter combinations
  - Checking for valid sets
- Sensitivity analysis
  - Checking the hypothesis with parameters
  - Checking if parameters influence results
- Hypothesis tests: Statistically testing the results of experiments

### Analysis

- Be neutral
- Always ask question about results, even if they are positive
- Search for additional sources
- Comment on unknown factors, don't hide them - they are means of finding the next topic to research on!

### Working with "Outliers"

- Don't remove or ignore them
- Test if they are relevant: Do more research - are they statistically relevant?
- If they are not relevant: Classify and document

### Comparisons

- The new is not automatically better
  - Comparison with a baseline reference is required
  - Detailed description of the reference system used is required
- Define the used dimensions for the comparison
  - Differences often occur in different dimensions
  - Elaborate why dimensions are being used
- Fair basis: i.e. not using an under powered server
- Also point out that the tool might perform worse under different dimensions (i.e. memory constrained systems)
- Comparison by
  - Comparison the reference solution and the new solution
  - Comparison of the new solution with existing literature

## Planning Scientific Papers

### Exposé

- Might be required
- Significant research requires planning
  - Assessment of feasibility
  - Usage of time slots
  - Focus on the most important goals or topics
- Short description of the planned research
  - Which problem is the basis of the planned research?
  - Prior, existing research and open questions
  - The main scientific question: Which question is the research going to answer?
  - Goal of the research
  - What theories is the research based on
  - Methods
  - Materials
  - Structure
  - How much time are the individual slots expected to take

### Structure

- Based on argumentation or path of discovery
- Balanced
- Not too much hierarchy
- Minimum length of the chapters and sections
- Total average ~50-60 pages
- Per chapter ~3-10 pages
- Typical:
  - Abstract (no section number, in both English and German)
  - Introduction (including overview)
  - Related work
  - Main investigation (multiple sections)
  - Results
  - Summary and conclusions
  - References

### Basic Procedure

- Clarification
  - Which questions should be answered?
  - What are the non-goals?
- Creating the project plan
- Getting up to date from a technical perspective
  - Which state is the research based on?
  - Search and analyzing papers
- Own works
  - Sometimes simply structuring the comparison
  - Normally: Experiments!
    - Definition
    - Execution
    - Analysis
- Selecting tools (BibTeX, LaTeX)
- Sketching
  - Creating a structure (i.e. mind maps)
  - Taking note of keywords and images
- Writing
  - Main section
  - Introduction
  - Abstract and summary
- Last checks

### Planning

- Every project needs planning
- Sketched planning needs to happen early in the project
  - Literature studies are often underestimated
  - Own works
  - Writing (min. four weeks before time is over!)
- More fine-tuned research with more knowledge
- Current state of research must be checked during own research
- Immediate active countermeasures are required
  - Plan must be changed
  - Asses severity of changes

### Planning the Main Section

- Structure is central
- Amount of pages per section is required
- Contents per section must be planned: Keywords, sources, images
- Writing takes time; start writing meta before actually starting to write

### Planning the Paper for this Module

- Formulating the scientific question
- Creating a structure
- Searching and analysising literature
- Refining the structure (two layers) including page numbers
- Selecting graphics (with sources)
- Writing
- Checking
- Submitting the paper
