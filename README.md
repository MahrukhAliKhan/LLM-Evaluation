# 🧠 LLM Evaluation Project
## 📌 Project Overview
This project provides a comprehensive framework for evaluating multiple Large Language Models (LLMs) using real-world QA datasets, standardized evaluation metrics, and custom critics. The goal is to compare the performance of different LLMs and identify the most effective model based on accuracy, reasoning, and overall utility in question-answering tasks.

## 🚀 Features
1. Integration with multiple LLM APIs including Groq.
2. Evaluation using a variety of metrics such as:
   - Answer Relevance
   - Contextual Understanding 
   - Hallucination Detection
3. Use of DeepEval and custom critics to assess LLM performance.
4. Generation of detailed evaluation reports.

## 📂 Dataset
- The dataset is loaded directly from Hugging Face Datasets.
- Task: Multiple-choice question answering.
- It serves as the input to all LLMs for consistent evaluation.

## 🧪 Steps Involved
1. Setup and Configuration  
Install and import necessary libraries.  
Configure environment variables for API access.  

2. Define Experimental Parameters  
Set parameters such as model names, temperature, top_p, and max tokens.  

3. Dataset Loading  
Fetch and preprocess the dataset from Hugging Face for downstream tasks.  

4. LLM Prediction  
Use different LLMs to generate answers for the dataset questions.  

5. Evaluation Metrics  
Apply both built-in and custom metrics using DeepEval to:  
- Answer Accuracy
- Measure relevance
- Detect hallucinations
- Evaluate coherence

6. Critic Model Integration  
A critic model is defined to analyze and score the outputs from LLMs.  

7. Reporting  
Generate structured reports comparing all evaluated models based on multiple metrics.  

## ⭐ Support
If you found this repository helpful, please consider starring it on GitHub!
Your support helps others discover this project and motivates further development. 🌟