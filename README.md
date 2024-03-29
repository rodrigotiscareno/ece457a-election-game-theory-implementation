# Tailoring Campaign Policies for Swing States Using Game Theory and Fuzzy Logic

**Authors:** Danick Carrier, Youssef Abadeer, Ria Patel, Inesh Jacob, Rodrigo Tiscareno, Myurah Senthilnathan

## Paper
[Fuzzy Logic and Game Theory Paper for US Swing States](https://www.overleaf.com/read/pnmbprpsqxpc#2f15b4)

## Summary
This project introduces an algorithm to predict strategic policy positions for Democratic and Republican candidates in essential swing states. The algorithm focuses on stances on key issues including healthcare, abortion, taxes, and climate, with the objective of improving candidates' electoral performance in these critical battlegrounds.

## Introduction
In the intricate landscape of American politics, swing states play a pivotal role in determining the outcome of presidential elections. These states, characterized by their fluctuating political allegiances, present a unique challenge for political candidates: the need to tailor their campaign strategies to a diverse and often unpredictable electorate. This paper introduces a computational algorithm that aims to address this challenge. By predicting the most effective campaign policies for Democratic and Republican candidates in these crucial battleground states, the algorithm seeks to enhance the strategic decision-making process in political campaigns. Leveraging the principles of game theory and fuzzy logic, it utilizes state-specific demographic data, such as GDP, education levels, religious preferences, and age demographics, to forecast the impact of various campaign policies on voter preferences.

The relevance of this research is highlighted by the changing dynamics of American political campaigns, where efficient resource allocation and strategic policy prioritization have become indispensable due to financial and time constraints. In a landscape where campaign policies can significantly sway public opinion, understanding the optimal policy for each swing state is vital for candidates. This paper delves into the development and potential applications of this algorithm, offering insights to navigate the complexities of modern political campaigns and contribute to a more data-driven approach to election strategy.

## Problem Statement
Candidates of a political party require a method to predict which campaign policy will be most effective in specific swing states to increase their probability of winning an upcoming election.

## Algorithms Used
1. Scripts to understand and analyze the political landscape of each swing state based on pre-existing datasets. This was done to predict policy decisions and the corresponding payoffs regarding taxes, climate change, healthcare, and abortion.
2. Fuzzy logic to create the payoff matrices for each policy decision per state.
3. Game theory to find all dominant strateges and nash equilibria per swing state 

## Prerequisites
1. Python 3.x
2. Libraries used in the import statements.

## Installation 
1. Clone the Repositiory.
2. Run the statistic_scripts .py files to produce the processed_data folder containing the CSVs.
3. Run the fuzzy.py and gametheory_v2.py files.
4. View the results in the generated txt files.

## Acknowledgment
The making of this project would only be possible with the teachings, lecture material and code inspired by Professor Benyamin Ghojogh.
