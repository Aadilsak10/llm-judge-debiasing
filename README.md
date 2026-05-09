# Difficulty-Aware Debiasing for LLM-as-a-Judge

A theoretical framework for correcting position bias in LLM-as-a-Judge evaluation systems.
Extends the Bradley-Terry pairwise comparison model with a judge-specific bias parameter 
scaled by instance difficulty, so harder comparisons receive stronger debiasing.

**Key contribution:** Bridges the empirical findings of Shi et al. (2024) on position bias 
with the statistical correction framework of Chen et al. (2026), proposing a two-stage 
estimation procedure validated through simulation (n=5,693 comparisons, 200 random seeds).

**Course:** MGMT 690 — Purdue University, 2026  
**Authors:** Aadil Sinju Abdul Kharim, Harshith Nagendra, Preetham Thirunavakkarasu
