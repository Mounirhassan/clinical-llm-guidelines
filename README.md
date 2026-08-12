# 🏥 Clinical LLM Guidelines & Prompt Engineering

![Status](https://img.shields.io/badge/Status-Active-success)
![Version](https://img.shields.io/badge/Version-1.0-blue)
![Focus](https://img.shields.io/badge/Focus-Clinical_AI%20%7C%20Pharmacy-purple)

## 🌟 Overview
Welcome to the **Clinical LLM Guidelines** repository. This project provides a structured framework for designing, evaluating, and optimizing Large Language Models (LLMs) specifically for clinical healthcare and pharmaceutical workflows. 

The goal is to bridge the gap between advanced prompt engineering and patient safety, ensuring AI outputs are accurate, medically sound, and free from hallucinations.

## 🎯 Core Objectives
1. **Zero-Hallucination Guardrails:** Strict prompt structures to prevent generative models from inventing clinical data.
2. **Medical Data Extraction:** Optimized workflows for extracting structured data from unstructured medical texts (e.g., prescriptions, patient histories).
3. **RLHF for Healthcare:** Evaluation criteria for Reinforcement Learning from Human Feedback in medical contexts.

---

## 🛠️ Advanced Prompt Templates

### 1. Prescription (Rx) Data Extraction & Verification
Use this prompt to accurately extract and verify medication data from unstructured text, ensuring pharmaceutical safety.

> **System Prompt:**
> You are an expert clinical pharmacist AI. Your task is to extract medication data from the provided text and output it STRICTLY in the following JSON format. Do not add conversational text. If a dosage is missing, flag it as "REQUIRES_CLARIFICATION".
> 
> **Input:** [Insert unstructured prescription text here]
> 
> **Expected Output Structure:**
> - Medication Name: 
> - Active Ingredient: 
> - Dosage & Frequency: 
> - Potential Interactions: 
> - Flags/Warnings: 

### 2. Clinical Case Summarization
> **System Prompt:**
> Act as a senior medical reviewer. Summarize the following patient history. Focus ONLY on actionable clinical insights, chronologically order the interventions, and highlight any contraindicated medications based on the patient's renal function.

---

## 📊 Evaluation Metrics (RLHF Guidelines)
When evaluating LLM outputs in clinical scenarios, human reviewers (AI Trainers) should grade responses based on:
- **Clinical Accuracy:** Does the output align with current medical guidelines?
- **Safety Over Helpfulness:** If a prompt asks for direct medical advice, the model must responsibly defer to a human healthcare provider.
- **Tone & Empathy:** Maintaining a professional, objective, yet empathetic clinical tone.

---

## 🚀 How to Use
You can fork this repository or copy the prompt templates directly into your preferred LLM interface (ChatGPT, Claude, Gemini). 

## 🧬 Clinical AI Evaluation (RLHF)
Explore my live dataset samples demonstrating how to evaluate LLMs for clinical safety, hallucination detection, and instruction adherence:
* **[👉 Click here to view the Clinical RLHF Dataset Sample](Clinical-RLHF-Sample.md)**

### 📖 Detailed Evaluation Methodology
Interested in the rubrics and methodology behind this evaluation? Check out my full evaluation framework:
* **[👉 View Clinical AI Evaluation Framework](https://github.com/Mounirhassan/clinical-ai-evaluation-framework)**

## 🛒 Available Books & Resources

If you find these guidelines helpful, you might be interested in my published works:

### 📖 Prescriptive AI: The Clinician's Complete Guide to Large Language Models in Healthcare
*A definitive guide for healthcare professionals on integrating LLMs safely into clinical workflows.*
*   **[Get it on Google Books ➡️](https://play.google.com/store/books/details/Mounir_S_Hassan_Prescriptive_AI?id=fiHaEQAAQBAJ)**



### 🧠 Psychology & Human Behavior
*   **[The Shadow Forge: How to Integrate Your Darkest Traits to Build an Unbreakable Legacy ➡️](https://play.google.com/store/books/details/Mounir_S_Hassan_THE_SHADOW_FORGE?id=HHjZEQAAQBAJ)**
*   **[The Anesthetic Age: How to Wake Up in a World...➡️](https://play.google.com/store/books/details/Mounir_S_Hassan_THE_ANESTHETIC_AGE?id=eprXEQAAQBAJ)**
*   **[The Silent Contracts: The Unwritten Rules That... ➡️](https://play.google.com/store/books/details/Mounir_S_Hassan_THE_SILENT_CONTRACTS?id=95jWEQAAQBAJ)**
*   **[Invisible Strings: How the World Secretly Hacks Your Mind, Wallet, and Free Will ➡️](https://play.google.com/store/books/details/Mounir_Hassan_Invisible_Strings?id=RvrVEQAAQBAJ)**
*   **[Mind Games, How Your Brain Deceives You: The... ➡️](https://play.google.com/store/books/details/Mounir_S_Hassan_Mind_Games_How_Your_Brain_Deceives?id=RUHVEQAAQBAJ)**


## 📬 About the Author
Created by a Clinical Pharmacist, AI Prompt Engineer, and LLM Evaluator passionate about the safe integration of Artificial Intelligence in healthcare.

*Feel free to star ⭐ this repository if you found it helpful!*
