# LPU Chat Build-a-thon 2023



# Law Information ChatBot based on Llama Index and ChatGPT

Welcome to the Law Information ChatBot project! This ChatBot utilizes Facebook's Llama Index for dataset indexing and ChatGpt for generating responses based on custom dataset input. It aims to provide information and answer questions related to law.

## Project Overview

The Law Information ChatBot is designed to assist users in retrieving relevant information about legal sections and information about it. It utilises the Indian Penal Code (IPC) and Code of Criminal Procedure (CRPC) as dataset on which chatgpt is trained. It combines the power of Llama Index, a dataset indexing library, and ChatGpt, a language model, to create an interactive conversational experience.

The project repository contains the necessary code and resources to run the ChatBot. Additionally, the dataset used for indexing is also provided.

## Repository Contents

- `Indian Law Information Chatbot.ipynb`: The main Python colab file that implements the ChatBot functionality using Llama Index and ChatGpt.
- `Context data/`: Directory containing the dataset files used for indexing.
- `README.md`: This file providing an overview of the project.
- Other supporting files and directories specific to the project.

## Requirements

To run the Law Information ChatBot, you'll need the following dependencies:

- Python 3.6 or above
- Llama Index library (llama-index==0.5.6)
- Langchain importing OpenAi (langchain==0.0.148)
- PyPDF2 (if your dataset is in pdf format it will help)

## Installation

Follow the steps below to set up and run the ChatBot:

1. Clone this repository to your local machine: or open it in colab and follow the instruction on the colab file.
2. For using other dataset simply provide url of your own github repo or upload it in colab storage or drive and make custom chatbot.

