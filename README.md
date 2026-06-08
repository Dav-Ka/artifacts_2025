# Self-Identification of Hallucinations in Small-Scale Large Language Models

## Project Overview

This project investigates whether small-scale open-source Large Language Models (LLMs) can recognize when their own responses are factually incorrect. The workflow includes dataset creation, model fine-tuning, answer generation, self-evaluation, and comparative analysis across multiple transformer-based models.

The objective is to better understand the relationship between a model's factual accuracy and its ability to identify its own hallucinations.

## Models Evaluated

- FLAN-T5-Small
- T5-Small
- OPT-125M

## Repository Structure

- `DatasetCreation_Final.ipynb`  
  Creates and prepares the dataset used for training and evaluation.

- `FLAN-T5-Small_Final.ipynb`  
  Fine-tunes and evaluates the FLAN-T5-Small model.

- `T5-Small_Final.ipynb`  
  Fine-tunes and evaluates the T5-Small model.

- `Opt-125_Final.ipynb`  
  Fine-tunes and evaluates the OPT-125M model.

- `Evaluation_Final.ipynb`  
  Aggregates experimental results and compares model performance across answer generation and self-assessment tasks.
