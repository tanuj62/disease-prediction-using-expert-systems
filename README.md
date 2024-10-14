# Disease-prediction-using-expert-systems
Implementations of  expert system using  meta-knowledge inference for diagnosing diseases based on symptoms in Python.
![WhatsApp Image 2024-10-10 at 10 56 24 PM](https://github.com/user-attachments/assets/bb5780bf-edd6-4b45-af0b-afa8ef972319)

# Medical Expert System for Disease Diagnosis  
This repository contains a **Medical Expert System** that diagnoses potential diseases based on the symptoms entered by the user. The system applies **meta-knowledge inference techniques** to match symptoms with predefined rules, suggesting exact or potential diagnoses accordingly.

## 💡 **Project Overview**  
An **Expert System** is an artificial intelligence (AI) application that emulates the decision-making ability of a human expert. This project focuses on **diagnosing diseases based on symptoms** using a rule-based inference engine. The system maintains a **knowledge base of diseases and their associated symptoms**. When the user provides symptoms, the engine matches them against the rules to suggest either an exact diagnosis or possible conditions.

## 🚀 **Features**  
- **Exact Diagnosis:** If the user's symptoms exactly match a rule, the system provides a definitive diagnosis.  
- **Potential Diagnoses:** The system suggests possible diseases if the symptoms are a subset of multiple rules.  
- **Friendly User Input:** The user can enter multiple symptoms individually and receive real-time feedback.  
- **No Match Handling:** The system notifies the user if no diagnosis can be made.

## 🔧 **Technologies & Tools Used**  
- **Python**: Programming language used to implement the expert system.  
- **PyCharm**: Integrated Development Environment (IDE) used for code development.  

## 📜 **Theory**  
The core of this project is based on **meta-knowledge inference**, which refers to the ability of the system to make inferences by matching rules to symptoms. Each rule in the system contains:  
1. A **disease name**.  
2. A **list of symptoms** associated with that disease.  

The inference engine follows a **forward chaining** approach:
- It compares the user's input with the predefined rules.
- If the symptoms **exactly match** a rule, the corresponding disease is diagnosed.
- If the symptoms form a **subset of multiple rules**, all matching diseases are suggested.
- If no match is found, the system notifies the user that no diagnosis can be made.

## 💻 **How to Use the Program**  
1. **Launch the program** by running the main script.  
2. Enter your **symptoms** one by one.  
3. Type **' done '** when you have finished entering symptoms.  
4. The system will provide an **exact or potential diagnosis** based on the symptoms entered.  
5. If no diagnosis can be made, the system will notify you.

## 🎯 **Conclusion**  
The **Medical Expert System** is an efficient way to assist in diagnosing diseases based on symptoms. Although it is not a replacement for professional medical advice, it provides a useful reference and support system for identifying potential health issues. This project demonstrates the application of **rule-based AI systems** and shows how **expert systems** can benefit healthcare by providing quick and preliminary diagnoses.

## 📚 **Future Improvements**  
- **Expand Knowledge Base:** Add more diseases and associated symptoms to improve accuracy.  
- **Probabilistic Inference:** Introduce probabilities to suggest the most likely diseases.  
- **GUI Development:** Build a graphical interface for easier interaction.  
- **Natural Language Processing (NLP):** Allow users to enter symptoms in natural language.  



