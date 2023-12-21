# MinerGuide

Miner Guide is a powerful tool designed to provide mining-related information by answering user queries using state-of-the-art language models and vector stores. 

MinerGuide is a Chatbot that responds to various text queries pertaining to various Acts, Rules, and Regulations applicable to the Mining Industries, offering a robust Management Information System. This not only enhances accessibility but also streamlines the compliance process, ensuring that the Mining industry operates within the bounds of the law. With a user-centric design our Chatbot endeavors to redefine the way stakeholders navigate the intricate legal landscape of the Mining industry.

This README will guide you through the setup and usage of the MinerGuide Bot.

## Table of Contents

- [Introduction](#minerguide)
- [Table of Contents](#table-of-contents)
- [Prerequisites](#prerequisites)
- [Installation](#installation)
- [Getting Started](#getting-started)
- [Usage](#usage)
- [Technologies Used](#technologies-used)
- [License](#license)

## Prerequisites

Before you can start using the MinerGuide Bot, make sure you have the following prerequisites installed on your system:

- Python 3.6 or higher
- Required Python packages (you can install them using pip):
  -  pypdf
  -  langchain
  -  torch
  -  accelerate
  -  bitsandbytes
  -  transformers
  -  sentence_transformers
  -  faiss_cpu
  -  chainlit
  -  huggingface_hub
  -  ctransformers

## Installation

1. Clone this repository to your local machine.

    ```bash
    git clone https://github.com/ParamD12/MinerGuide.git
    cd MinerGuide
    ```

2. Create a Python virtual environment (optional but recommended):

    ```bash
    python -m venv venv
    source venv/bin/activate  # On Windows, use: venv\Scripts\activate
    ```

3. Install the required Python packages:

    ```bash
    pip install -r requirements.txt
    ```

4. Download the required language models and data. Please refer to the Langchain documentation for specific instructions on how to download and set up the language model and vector store.

5. Download the required language model(Llama 2 7B Chat), in the same folder as this repository. Please refer to the Langchain documentation for specific instructions on how to download and set up the language model and vector store.

6. Set up the necessary paths and configurations in your project, including the `DB_FAISS_PATH` variable and other configurations as per your needs.

## Getting Started

To get started with the MinerGuide Bot, you need to:

1. Set up your environment and install the required packages as described in the Installation section.

2. Configure your project by updating the `DB_FAISS_PATH` variable and any other custom configurations in the code.

3. Prepare the language model and data as per the Langchain documentation.

4. Start the bot by running the provided Python script or integrating it into your application.

## Usage

The MinerGuide Bot can be used for answering mining-related queries. To use the bot, you can follow these steps:

1. Start the bot by running your application or using the provided Python script.

2. Send a mining-related query to the bot.

3. The bot will provide a response based on the information available in its database, which consists of various Acts, Rules, and Regulations corresponding to the Mining Industry.

4. If sources are found, they will be provided alongside the answer.

5. The bot can be customized to return specific information based on the query and context provided.

## Technologies Used

1. **Llama 2**: Llama 2 is a state-of-the-art NLP model, is employed for natural language understanding, allowing the Chatbot to interpret user queries accurately and provide context-aware responses.

2. **Sentence Transformers**: Sentence Transformers are utilized to enable semantic search and recommendation capabilities, ensuring that users receive relevant and context-aware information.

3. **Chainlit**: Chainlit is the framework used to create the user interface for the Chatbot. It provides an intuitive and user-friendly platform for users to interact with the application.

4. **Hugging Face**: Hugging Face is a platform known for hosting pre-trained NLP models, including Llama 2. It provides a valuable resource for accessing and using these models in your project.

5. **FAISS (CPU)**: FAISS, a library for efficient similarity search, is harnessed to enhance the Chatbot's performance, enabling quicker search and retrieval of relevant information. It runs on a CPU, ensuring broad accessibility.

6. **Langchain**: Langchain, a crucial component, contributes to the project's natural language processing capabilities, aiding in understanding and interpreting user queries related to the mining industry in India.

## License

This project is licensed under the MIT License.

---

For more information on how to use, configure, and extend the MinerGuide Bot, please refer to the Langchain documentation or contact the project maintainers.
