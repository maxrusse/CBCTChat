# CBCTChat - A Content-Aware Chatbot Based on GPT-4 for the German S2 Cone-Beam CT (CBCT) Dental Imaging Guideline

## Introduction

**CBCTChat** is an AI-powered chatbot designed to offer insights and information on the German S2 Cone-Beam CT (CBCT) dental imaging guideline. Utilizing the capabilities of LLamaIndex combined with OpenAI’s GPT-3.5-Turbo and GPT-4 models, this chatbot delivers answers grounded in specialized knowledge through an embedding-based knowledge retrieval method.

## Features

- **QA Queries**: The system can query CBCTChat based on GPT-3.5-Turbo and GPT-4 models, retrieving context-based answers in a Question-Answer style.
- **German Language**: Designed with German language prompts for seamless integration with the German S2 CBCT guideline.
- **Interactive Jupyter Notebook**: An easy-to-use Jupyter notebook that allows users to create an index, set parameters, and view results of CBCTChat.
- **PDF Metadata Extraction**: Extracts metadata from the guideline PDF, enabling context for the AI's responses.

## Prerequisites

Before running the provided Jupyter notebook:

- Ensure you have an OpenAI API key. You can obtain one from [OpenAI](https://platform.openai.com/account/api-keys).
- Copy the German S2 CBCT Guideline into the `data` folder.
- Install the required Python libraries either by running the notebook cells or using pip.

## Usage

1. Open the `Demo of CBCTChat.ipynb` notebook in your preferred Jupyter environment, such as Google Colab or JupyterLab.
2. Follow the instructions within the notebook to set up the OpenAI API key.
3. Execute the notebook cells to initialize the system and interact with the chatbot.

## Important Notes

- **Data Privacy**: Ensure you understand the ethical and legal implications related to patient privacy, data protection, and the sources you utilize.
- **Not for Medical Use**: The answers provided by `CBCTChat` are for demonstration and research purposes only. They should not replace professional medical advice, diagnosis, or treatment. Always consult with a qualified healthcare provider for any medical concerns.


## Acknowledgments

- OpenAI for providing the GPT models and API.
- [Link to the full publication (Update when available)](<Your publication link here>)

## License:

This project is licensed under the MIT License. Please refer to the LICENSE file in the repository for more details.
