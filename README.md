Article Summarizer with AI Assistant
This repository contains a Python script that utilizes artificial intelligence to summarize online articles. It leverages a combination of web scraping, natural language processing, and AI-powered chat models to create an intelligent assistant capable of generating concise summaries.

Features
Fetches article content from a specified URL using web scraping techniques
Extracts the title and text of the article for summarization
Utilizes a pre-trained AI model ("gpt-4") for generating summaries
Supports prompts in different formats and languages
Provides options for generating summaries in bulleted list format and in French
Setup and Dependencies
The script requires the following dependencies, which can be installed using pip:

python-dotenv: For managing environment variables
openai: Provides access to the AI model for generating summaries
langchain: Includes schema and chat models for interacting with the AI model
newspaper3k: Enables web scraping and article parsing functionalities
Usage
Install the required packages by running pip install -r requirements.txt.
Set up your OpenAI API key by creating a .env file with your API key in the format OPENAI_API_KEY='<YOUR_API_KEY>'.
Modify the article_urls variable in the script to specify the URL of the article you want to summarize.
Run the script using python article_summarizer.py.
The script will fetch the article, generate a summary using the AI model, and print the results.
Contributing
Contributions to the project are welcome. If you have any suggestions, bug reports, or feature requests, please open an issue or submit a pull request.

License
This project is licensed under the MIT License.

Disclaimer
Please note that the AI model used in this project is provided by OpenAI and may have limitations or biases. Use the generated summaries with discretion and review the results for accuracy and appropriateness.

Acknowledgments
The script makes use of the following libraries and frameworks:

OpenAI - Provides the AI model for generating summaries
langchain - A Python library for interacting with language models
newspaper3k - Library for web scraping and article parsing

Feel free to explore and contribute to this project!
