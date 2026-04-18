This ReadME file contains my Assignment #3 data.

# Text Analysis Project - Fine-Tuned Classifier Models via LLM Encoder - Sara Murphy

This GitHub contains all of the data files and documents write-ups for Sara's LLM project for Computational Text Analysis.

This repository includes both the answers to Assignment #3, which relied at times upon an earlier stage version of the data, and the Final Project.

Both projects relate to the context of Canadian public universities, trying to assess how they perceive their "resource dependence" upon the government who provides the majority of their funding. Specifically, in the province of Ontario, public universities have experienced a policy shock since 2019 that some universities have attributed to poor financial performance. This project aims to explore how dependence operates as a subjective construct rooted in leader perceptions, which in turn may shape the strategic action and financial performance of public universities.


# ASSIGNMENT 3
Part 1 of this Assignment involved building a small corpus of 200 observations total to practice hand coding and using an LLM as an annotator. Relies upon Google Colab code provided in class.

Part 2 of this Assignment involved building up observations to 200 per class and then making predictions on a sample outside of the corpus. Relies upon Google Colab code provided in class.

# Data
Data folder within the Assignment 3 folder contains:
- trainingmodel_ontario_budgets_v4_llm_sample.xlsx - this is the data I hand coded and used in Google CoLab
- llm_all_predictions.xlsx - this is the exported predictions from the 3 LLM models. Contains comparison/variance columns to highlight differences between human and LLM coding
- R Markdown file and knitted R html file used to calculate intercoder reliability

Google Colab links are found within the assignment write-up (see Docs). Also included here for convenience as public, shareable links.

# Docs
Contains Assignment 3 write-up as word doc and pdf.


# FINAL PROJECT
This project designs two fine-tuned binary classifier models to detect the presence of perceptions of resource dependence langauge (0,1) as well as the intensity of these perceptions (low, high). 

# Data
Contains all excel files used, which represent the corpus at different stages of development. Some are work-in-progress files and others are "semi-final" versions which were then used for fine-tuning.
- V14, V18, V23 and V24 represent 4 excel versions used in the fine-tuning code shared from Google Colab

Google Colab links are included within the final project write-up (see docs). They are also copied here for convenience. These have been shared to be public, viewable links. Google Colab was used (following an in-class template) to fine-tune the model over 4 phases, involving 4 different versions of the corpus.

Phase 1 (V14)
- https://colab.research.google.com/drive/1ne8x5RwFtfyBC0FiBR7FTyK9Cht0pf6b?usp=sharing
- https://colab.research.google.com/drive/1DCJ9hH_0fnHnp3BK3-1SGirTbLpUy3Lc?usp=sharing

Phase 2 (V18)
- https://colab.research.google.com/drive/1F0GKUYFUddvNyW7CvoQ4v9SZyGngC66Y?usp=sharing
- https://colab.research.google.com/drive/1ZLPWiWnVqOs6qh85p34BP0QQ1AbC1vvm?usp=sharing

Phase 3 (V23)
- https://colab.research.google.com/drive/1wSY9O0TM6ihYmrEVQsAlQZjkBuFvwvEr?usp=sharing
- https://colab.research.google.com/drive/15O3brOUET6hGXI3q8ToqIkKaNpi4aTdS?usp=sharing

Phase 4 (V24)
- https://colab.research.google.com/drive/10LrJvlT0cmnDutLtlVwm6vEZ2Y7NFF0R?usp=sharing
- https://colab.research.google.com/drive/1_lk_cvCMehdLEemOvasTSZy2qSX02Pfg?usp=sharing

# Docs
- Contains the final essay (4,000 words + references + appendices) as a word doc and pdf.
- Contains in-class presentation as a powerpoint and pdf. 
