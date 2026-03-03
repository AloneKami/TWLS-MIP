# TWLS-MIP Artifact

This repository contains the artifact accompanying the submission:

> **Enhancing Local Search with Two Distinct Scoring for Mixed Integer Programming**

To preserve double-blind reviewing, the source code will be publicly released after acceptance.

TWLS-MIP is a local search solver for Mixed Integer Programming (MIP).

This artifact provides:

- A precompiled executable of TWLS-MIP
- The detailed experimental results reported in the paper

---

Running the Solver

A precompiled executable `TWLS-MIP` is provided.

## Basic Usage

./TWLS-MIP --instance=[file] --cutoff=[time limit]

Required Parameters

--instance=[file]
Path to the input MIP instance file (e.g., .mps, .lp).

--cutoff=[time limit]
Time limit in seconds.

Example

./TWLS-MIP --instance=2club200v15p5scn.mps --cutoff=600
