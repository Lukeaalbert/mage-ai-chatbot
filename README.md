# Potions & Other Wizardly Things AI Shopping Assistant

This repo serves as an AI shopping assistant for a fictional shop called "Potions & Other Wizardly Things." It utilizes the OpenAI API to interact with users, providing information about items in stock, handling customer service queries, detecting malicious intent in user inputs, and even storing the type of user inquiries in a .txt file for user analytics.

Although the idea of a "Potions & Other Wizardly Things" AI Shopping Assistant is silly, this repo serves as a skeleton for any AI customer service chat bot that uses OpenAI APIs.

- **Item Information**: 
  The script provides information about items in stock, including their prices and descriptions. These can be changed to whatever products the user wants.
  
- **Customer Service Handling**: 
  It categorizes customer queries into primary and secondary categories and outputs the classification in JSON format to a .txt file.

- **Malicious Intent Detection**: 
  It checks for malicious intent in user inputs to prevent prompt injections or malicious instructions.

## Setup

Before using the script, ensure you have the following dependencies installed, which you can via pip:

```bash
pip install -r requirements.txt

Additionally, make sure you have an OpenAI API key. You can obtain one by signing up at OpenAI's website.
Create a .env file in the same directory as the script and add your OpenAI API key:

```bash
OPENAI_API_KEY=your-api-key-goes-here
