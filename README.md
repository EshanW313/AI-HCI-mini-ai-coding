# AI-HCI: Mini COding Assignment (API Integration)

## What it does
This repository contains a Jupyter Notebook (`AI_HCI_coding_1.ipynb`) that utilizes Google Gemini model to generate textual responses based on user prompts.

## Setup instructions and how to run
### Prerequisites
- Install this dependency using this code:
  ``` python
  pip install google-generativeai
  ```
- Get a [Gemini API key](https://ai.google.dev/gemini-api/docs/api-key)

### Instructions
1. Download the `AI_HCI_coding_1.ipynb` file from this repository
2. Open the Jupyter notebook file on Google Colab, Visual Studio Code, or any other Jupyter-supporting IDE
3. Replace the "ENTER YOUR API KEY HERE" text (in the second cell) with your Gemini API key
4. Run the code cells sequentially

### How the program works
1. Program will ask you to enter text which will serve as the initial prompt to the Gemini model
2. Gemini will process the prompt and generate a response within a few seconds
3. Conversation will continue by entering new prompts and Gemini will respond to each one (maintains context from previous interactions)
4. Type "history" (lowercase) to see a list of all the prompts you have entered in that session
5. Type "bye", "exit", "goodbye", or "quit" (case-insensitive) to end the chat/session

