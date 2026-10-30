# SDG Solver Demo

This repository contains a demonstration program for causal diagnosis using Signed Directed Graphs (SDG).

## Contents

- `SDG_Solver_V4.2_distribution_3patterns.zip`
  - SDG solver
  - two-tank model
  - three sample patterns
  - Windows `run.bat`

## How to use

1. Download the ZIP file.
2. Extract the ZIP.
3. On Windows, double-click `run.bat`.
4. Select one of the three sample patterns.

You can also run from the command line:

python SDG_solver.py -t sdg1.data pattern1.data

## Sample patterns

- Pattern 1: F1 decrease
- Pattern 2: F0 increase
- Pattern 3: F2 decrease

## Purpose

This demo is intended to help users understand how SDG-based causal diagnosis identifies a root cause and an effective rooted tree from observed symptoms.
