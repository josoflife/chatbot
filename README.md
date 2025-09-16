# chatbot
📋 Overview

The Health Chatbot asks the user to input their symptoms (e.g., fever, cough) and then:
Compares the entered symptoms to a predefined knowledge base of common diseases.
Returns any diseases where all required symptoms match.
Prints helpful advice for each possible disease.
________________________________________________________
🛠️ Features

Preloaded Knowledge Base: Flu, Common Cold, Malaria, COVID-19, and Strep Throat.
Symptom Matching: Matches only when all key symptoms of a disease are present.
Advice Output: Provides multiple self-care tips for each matching disease.
________________________________________________________
📂 Project Structure
health_chatbot/
├─ health_chatbot.py   # Main Python script
└─ README.md           # Project documentation (this file)

▶️ Requirements

Python 3.6 or higher
________________________________________________________

🚀 How to Run

Clone or Download this repository.

Open a terminal/command prompt in the project folder.

Run:

python health_chatbot.py

When prompted, enter your symptoms separated by commas:

Symptoms: fever, cough, sore_throat
________________________________________________________
🧩 How It Works

Input Handling
The program asks for symptoms as a comma-separated list.
Example: fever, cough, sore_throat

-Disease Inference
infer_disease() checks if all required symptoms for a disease are in the user’s input.

-Advice Display
If a match is found, it prints the disease name and its associated advice from advice_base.
________________________________________________________
🔧 Customization

Add New Diseases

Edit the knowledge_base and advice_base dictionaries in health_chatbot.py.

Modify Symptoms
-Adjust symptom lists as needed for more accurate matching.
