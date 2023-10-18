# DocScribe
An AI chatbot to help medical professionals with medical reports summarization

# Medical QA Chatbot using LLM

## Introduction
We aim to develop a medical QA chatbot that can respond quickly and accurately to general medical and patient-specific queries.

## Table of Contents
1. [Objectives](#objectives)
2. [Architecture](#architecture)
3. [Data Sources & Data Samples](#data-sources--data-samples)
4. [Live Demo](#live-demo)
5. [Modeling Approach](#modeling-approach)
6. [Results](#results)
7. [Conclusions](#conclusions)
8. [Recommendations & Future Work](#recommendations--future-work)

## Objectives
- Patient History Retrieval
  - Interact with medical transcripts
  - Extract insights based on patient history
- Medical QnA
  - Ask general medical queries
  - Learn about drug interactions, medical conditions, etc.
- DocScribe
  - Report Summarization
  - Summarize reports from multiple visits
  - Identify relevant information
- Transcribe Medical Reports
  - Convert patient medical report into a more accessible format
  - Making it easier to interpret data from Medical Reports

## Data Sources & Data Samples
- **Medical Transcripts**
  - We leveraged the GPT-3.5 model to generate 4.5k QA prompts from the medical transcripts (MTSamples dataset).
- **WikiDoc**
  - WikiDoc is a platform for medical professionals to contribute and edit medical content.
  - 10k QnA prompts.
- **WikiPatient**
  - WikiPatient is a platform for patients to access information and education about diseases.
  - 5K QnA prompts.

## Modeling Approach
**Approach:**
- Model: Fine-tuning Vicuna-13B
- Training: LoRA, PEFT, bitsandbytes
- Hyperparameters: Same as Alpaca

**Frameworks:**
- LLM Components: LangChain
- Weights: HuggingFace
- Training: PyTorch
- Embeddings: all-mpnet-base-V2
- Vector database: Qdrant

## Results
Our model has successfully achieved its objectives of extracting patient information, generating report summaries, and answering general medical questions.

## Model Improvement Research
- Training base model on medical corpus and incorporating human feedback.
- Explore the use of the medical LLM for research and clinical trials, including medical image analysis.

## Thank You!
We appreciate your interest in our project and thank you for your support!

For more information and to access the codebase, please visit our GitHub repository.

[WIP]: More details to be added soon
