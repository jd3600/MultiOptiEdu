**Project: MultiOptiEdu**

*Heuristic Model of Number Decomposition by Tabular Representation (MHDN-RT)*

--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------



1\. Project Introduction

The MultiOptiEdu project offers an innovative approach to the teaching and understanding of numerical relationships. It explores how a simple visual representation, derived from multiplication tables, can be formalized into a powerful algorithm for determining the Greatest Common Divisor (GCD). This project demonstrates the translation of a visual intuition into an effective and adaptable computational solution.



--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------



2\. The Concept: From Visualization to Algorithm

The central concept of this project is based on the idea that divisibility relationships can be perceived as a pattern in a graph. The algorithm developed is a direct translation of this observation: instead of using complex formulas, it replicates the process of finding common divisors in a numerical way. The MHDN-RT is thus a proof of concept that visual ideas can be the source of algorithmic innovations.



--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------



3\. Visual Component

This component uses the matplotlib library to generate a mapping of multiplication tables. There are two versions:



visualisation\_basique.py : Displays the products of tables 1 to 10 up to 100.



visualisation\_étendue.py : Distinguishes between standard multipliers (≤ 10) and extended multipliers (> 10) for more in-depth analysis.



--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------



4\. Algorithmic Component

This component is the implementation of the Minimalist GCD Algorithm. This Python script is designed to be a standalone tool, asking the user to enter as many numbers as they wish to find their GCD.



Minimalist: Displays only the information relevant to the analysis.



Adaptive: Works with an unlimited number of integers.



Educational: Clearly demonstrates the logic of common divisors before presenting the final result.



--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------



5\. Usage

Prerequisites

The project requires the following Python libraries:



* numpy
* matplotlib



To install them, run the command:



Bash



pip install numpy matplotlib



How to run

* For the visualization, run the desired script (visualisation\_basique.py or visualisation\_étendue.py).
* For the GCD algorithm, run the script pgcd\_algorithme.py and follow the on-screen instructions. Type / to finish entering numbers.



--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------



6\. Project Structure

The project is organized as follows:



README.md : This documentation file.



Multioptedu.ypnb : Code for the extended graph & basic graph..



multioptedu.py : Code for the GCD algorithm.



--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------



