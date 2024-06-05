---
layout: archive
title: "Tools and Datasets"
permalink: /tools/
author_profile: true
---

*If you use any of the tools and datasets provided here, please cite the corresponding paper.*

## Datasets

[Syn-vs-Sem:](https://mutationtesting-user.github.io/bugs_vs_mutants/) dataset used for studying the syntactic and semantic similarities between real and artificial faults (TSE 2022).

[Commit-relevant mutants:](https://mutationtesting-user.github.io/evolve-mutation.github.io/) dataset employed in our exploratory study (TOSEM 2022).

[Vulnerability-coupling-mutants:](https://github.com/garghub/VulnerabilityCouplingMutants) dataset used to study the coupling between vulnerabilities and LLM-generated mutants (ICST 2024).

## Testing

[μBERT](https://github.com/rdegiovanni/mBERT) is a mutation testing tool that uses CodeBERT, a pre-trained language model, to generate mutants (Mutation 2022). 

[Cerebro](https://github.com/garghub/Cerebro) is a machine learning approach that statically selects subsuming mutants, i.e., the set of mutants that resides on the top of the subsumption hierarchy, based on the mutants' surrounding code context (TSE 2021). 

[Trovon](https://github.com/garghub/TROVON) is a vulnerability prediction technique that learns from known vulnerable components rather than from vulnerable and non-vulnerable components, as typically performed (EMSE 2022). 


## Requirements Analysis

[SpecBCFuzz](https://github.com/SpecBCFuzz/repo) implements a search-based algorithm that fuzzes LTL formulas giving relevance to boundary conditions to test LTL solvers (ICSE 2024). 

[AuRUS](https://sites.google.com/site/unrealrepair/) is a tool that implements a multi-objective genetic algorithm to repair unrealisable LTL specifications (GECCO 2023).

[ACoRe](https://sites.google.com/view/acore-2022) is a tool that implements multi-objective search algorithms for resolving goal-conflicts in formal requirements specifications (FASE 2023). 

[BCLearner](http://dc.exa.unrc.edu.ar/staff/rdegiovanni/ASE2018.html) implements a genetic algorithm for identifying goal conflicts (ASE 2018).

[BCTableaux](https://dc.exa.unrc.edu.ar/staff/rdegiovanni/ase2016.html) implements a satisfiability tableaux-based algorithm for computing goal-conflicts (ASE 2016). 

This [tool](http://dc.exa.unrc.edu.ar/staff/rdegiovanni/ICSE2018.html) can be used for assessing the likelihood and severity of goal-conflicts by using model counting (ICSE 2018).

[Here](https://dc.exa.unrc.edu.ar/staff/rdegiovanni/case-studies/ICSE2014.zip) we provide the dataset and the experimental results of our automatic Goal Operationalisation approach (ICSE 2014).

[CLTSA](http://dc.exa.unrc.edu.ar/tools/cltsa) is a Labelled Transition System Analyser with Counting Fluents Support (ICSE 2015 and FSE 2017).

This [tool](https://dc.exa.unrc.edu.ar/staff/rdegiovanni/case-studies/SCR_Analysis.zip) implements an automatic abstraction process to analyse SCR requirements specifications. It can be use for verification or test generation (TAP 2011 and STVR 2018).

## Specification Inference

[MemoRIA](https://zenodo.org/records/10683011) implements a novel approach that combines program abstraction, fuzzing, dynamic analysis and SAT solving, to automatically infer metamorphic relations of Java programs (FSE 2024).

[DeltaSpec](https://sites.google.com/view/delta-spec/) implements an approach that combines test generation and dynamic specification inference to automatically compute commit-relevant specifications (delta specs) for given commits. 

[Seeker](https://github.com/garghub/seeker) implements a transformer-based approach to select assertion inferring mutants (ISSRE 2023).

[LearningClassInvariants](https://sites.google.com/site/learninginvariants) implements a ML approach to build a binary classifier to distinguish valid from invalid data structure objects, i.e., the class invariant (ICSE 2019).

