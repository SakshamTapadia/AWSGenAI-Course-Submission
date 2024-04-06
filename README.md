# Udacity Generative AI with AWS Course

## Amazon SageMaker: Fine-tuning Llama2 Large Language Model

### Overview

This project focuses on fine-tuning the Llama2 Large Language Model using Amazon SageMaker, specifically tailored for the financial domain. Below are the essential steps and outcomes:

### 1) Evaluation of Pre-trained Model

- **Notebook Instance Type Utilized:** `ml.t3.medium`
- **Amazon EC2 G5 instance Employed:** `ml.g5.2xlarge`

#### Steps:

1. **Deployment of Llama2 Model on AWS SageMaker:**
   - Utilization of the pre-trained Llama2 Text Generation Large Language Model.

2. **Assessment of Pre-trained Llama2 Model for Financial Domain Knowledge:**
   - Evaluation using domain-specific inputs.
   - **Input:** "The results are encouraging for aggressive investors"
   - **Model Response:** "For those inclined towards aggressive investment, the current stock trades at $31.40, marking a 45.6% increase from the 52-week low of $21.67 and a 66.4% increase from the 52-week high."

### 2) Fine-tuning of Large Language Model

- Fine-tuning of a Large Language Model with a Financial Domain-Specific Dataset.

### 3) Evaluation of the Fine-tuned Llama2 Large Language Model

- Deployment of the Fine-tuned Llama2 Model on AWS SageMaker.
- Evaluation of the Fine-tuned Llama2 Text Generation Large Language Model on Text Generation Tasks and Financial Domain Knowledge.

#### Steps:

1. **Domain-specific Input:**
   - "The results are encouraging for aggressive investors."

2. **Model Response:**
   - "The S&P 500 has seen a 14% increase this year, but it's not the only index showing strong performance. The S&P Midcap 400 has surged by 16% in 2019, showcasing robust growth alongside the S&P."
