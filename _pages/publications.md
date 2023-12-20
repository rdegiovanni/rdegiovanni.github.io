---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

## 2024
Luiz Carvalho, Renzo Degiovanni, Maxime Cordy, Nazareno Aguirre, Yves Le Traon, Mike Papadakis. ["SpecBCFuzz: Fuzzing LTL Solvers with Boundary Conditions"](), in the 46th International Conference on Software Engineering (ICSE), 2024.

Aayush Garg, Renzo Degiovanni, Mike Papadakis and Yves Le Traon. ["On the Coupling between Vulnerabilities and LLM-generated Mutants: A Study on Vul4J dataset"](), in the 17th IEEE International Conference on Software Testing, Verification and Validation (ICST), 2024.

## 2023
Aayush Garg, Renzo Degiovanni, Facundo Molina, Maxime Cordy, Nazareno Aguirre, Mike Papadakis and Yves Le Traon. ["Enabling Efficient Assertion Inference"](files/ISSRE23.pdf), in the 34th IEEE International Symposium on Software Reliability Engineering (ISSRE), 2023.

Milos Ojdanic, Aayush Garg, Ahmed Khanfir, Renzo Degiovanni, Mike Papadakis and Yves Le Traon. ["Syntactic Vs. Semantic similarity of Artificial and Real Faults in Mutation Testing Studies"](https://ieeexplore.ieee.org/document/10136793), in the IEEE Transactions on Software Engineering Journal (TSE).

Matias Brizzio, Maxime Cordy, Mike Papadakis, Cesar Sanchez, Nazareno Aguirre, Renzo Degiovanni. ["Automated Repair of Unrealisable LTL Specifications Guided by Model Counting"](https://dl.acm.org/doi/10.1145/3583131.3590454), in the The Genetic and Evolutionary Computation Conference (GECCO), 2023.


Milos Ojdanic, Aayush Garg, Ahmed Khanfir, Renzo Degiovanni, Mike Papadakis and Yves Le Traon. ["On Comparing Mutation Testing Tools through Learning-based Mutant Selection"](files/AST2023.pdf), in the 4th ACM/IEEE International Conference on Automation of Software Test (AST), 2023.


Luiz Carvalho, Renzo Degiovanni, Matias Brizzio, Maxime Cordy, Nazareno Aguirre, Yves Le Traon, Mike Papadakis. ["ACoRe: Automated Goal-Conflict Resolution"](https://arxiv.org/pdf/2303.05213.pdf), in the 26th International Conference on Fundamental Approaches to Software Engineering (FASE), 2023.

## 2022

Milos Ojdanic, Ezekiel Soremekun, Renzo Degiovanni, Mike Papadakis and Yves Le Traon. ["Mutation Testing in Evolving Systems: Studying the relevance of mutants to code evolution"](https://dl.acm.org/doi/pdf/10.1145/3530786), in the ACM Transactions on Software Engineering and Methodology Journal (TOSEM).

Aayush Garg, Renzo Degiovanni, Matthieu Jimenez, Maxime Cordy, Mike Papadakis, Yves Le Traon.  ["Learning from What We Know: How to Perform Vulnerability Prediction using Noisy Historical Data"](https://link.springer.com/article/10.1007/s10664-022-10197-4),  in Empirical Software Engineering Journal (EMSE).

Renzo Degiovanni and Mike Papadakis. ["μBERT: Mutation Testing using Pre-Trained Language Models"](https://arxiv.org/pdf/2203.03289), in the 17th International Workshop on Mutation Analysis (MUTATION), 2022.

## 2021

Aayush Garg, Milos Ojdanic, Renzo Degiovanni, Thierry Titcheu Chekam, Mike Papadakis, Yves Le Traon. ["Cerebro: Static Subsuming Mutant Selection"](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9677967), in the IEEE Transactions on Software Engineering Journal (TSE).

## 2019

Facundo Molina, Renzo Degiovanni, Pablo Ponzio, Germán Regis, Nazareno Aguirre, Marcelo F. Frias. ["Training Binary Classifiers as Data Structure Invariants"](https://orbilu.uni.lu/bitstream/10993/41037/1/learning-invariants.pdf), in the 41st International Conference on Software Engineering (ICSE).

Facundo Molina, César Cornejo, Renzo Degiovanni, Germán Regis, Pablo F. Castro, Nazareno Aguirre. ["An evolutionary approach to translating operational specifications into declarative specifications"](https://orbilu.uni.lu/bitstream/10993/41038/1/learning-alloy-specs.pdf), in Journal of Science of Computer Programming (SCP).

## 2018

Renzo Degiovanni, Pablo F. Castro, Marcelo Arroyo, Marcelo Ruiz, Nazareno Aguirre, Marcelo F. Frias. ["Goal-conflict likelihood assessment based on model counting"](files/ICSE2018.pdf), in the 40th International Conference on Software Engineering (ICSE).

Renzo Degiovanni, Facundo Molina, Germán Regis, Nazareno Aguirre. ["A genetic algorithm for goal-conflict identification"](files/ASE2018.pdf), in the 33rd ACM/IEEE International Conference on Automated Software Engineering (ASE).


Renzo Degiovanni, Pablo Ponzio, Nazareno Aguirre, Marcelo F. Frias. ["Improving lazy abstraction for SCR specifications through constraint relaxation"](files/STVR2018.pdf). in Software: Testing, Verification and Reliability (STVR).

Facundo Molina, Renzo Degiovanni, Germán Regis, Pablo F. Castro, Nazareno Aguirre, Marcelo F. Frias. ["From operational to declarative specifications using a genetic algorithm"](files/SBST2018.pdf). in 11th International Workshop on Search-Based Software Testing (SBST).

## 2017

Germán Regis, Renzo Degiovanni, Nicolás D'Ippolito, Nazareno Aguirre. ["CLTSA: labelled transition system analyser with counting fluent support"](files/CLTSATool.pdf), in the 11th Joint Meeting on Foundations of Software Engineering (ESEC/FSE) - tool paper.

Luciano Zemín, Simón Gutiérrez Brida, Ariel Godio, César Cornejo, Renzo Degiovanni, Germán Regis, Nazareno Aguirre, Marcelo F. Frias. ["An Analysis of the Suitability of Test-Based Patch Acceptance Criteria"](files/SBST2017.pdf), in the 10th IEEE/ACM International Workshop on Search-Based Software Testing (SBST).

## 2016

Renzo Degiovanni, Nicolás Ricci, Dalal Alrajeh, Pablo F. Castro, Nazareno Aguirre. ["Goal-Conflict Detection based on Temporal Satisfiability Checking"](files/ASE2016.pdf), in the 
31st IEEE/ACM International Conference on Automated Software Engineering (ASE).

Facundo Molina, César Cornejo, Renzo Degiovanni, Germán Regis, Pablo F. Castro, Nazareno Aguirre, Marcelo F. Frias. ["An Evolutionary Approach to Translate Operational Specifications into Declarative Specifications"](files/SBMF2016.pdf), in the 19th Brazilian Symposium Formal Methods (SBMF).

## 2015

Germán Regis, Renzo Degiovanni, Nicolás D'Ippolito, Nazareno Aguirre. ["Specifying Event-Based Systems with a Counting Fluent Temporal Logic"](files/ICSE2015.pdf), in the 37th International Conference on Software Engineering (ICSE).

## 2014

Renzo Degiovanni, Dalal Alrajeh, Nazareno Aguirre, Sebastián Uchitel. ["Automated Goal Operationalisation based on Interpolation and SAT Solving"](files/ICSE2014.pdf), in the 36th International Conference on Software Engineering (ICSE).

## 2013

Gastón Scilingo, María Marta Novaira, Renzo Degiovanni, Nazareno Aguirre. ["Analyzing Behavioural Scenarios over Tabular Specifications Using Model Checking"](files/LAFM2013.pdf), in the 1st Latin American Workshop on Formal Methods (LAFM).

Gastón Scilingo, María Marta Novaira, Renzo Degiovanni. ["Analizando Especificaciones Formales de Requisitos de Software usando un Model Checker Off-the-Shelf"](files/CLEI2013.pdf), in the 39th Conferencia Latinoamericana en Informática (CLEI).

## 2011

Renzo Degiovanni, Pablo Ponzio, Nazareno Aguirre, Marcelo Frias. ["Abstraction based Automated Test Generation from Formal Tabular Requirements Specifications"](files/TAP11.pdf), in the 5th International Conference Tests and Proofs (TAP).



