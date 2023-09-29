# ArticleWriter

A Jupyter Notebook that will write an article using ChatGPT

This project demonstrates how to use the OpenAI GPT-3.5 Turbo model, also known as ChatGPT, to automatically generate articles based on user-defined topics or keywords. With this implementation, you can quickly create draft articles, including section titles, related keywords, and HTML formatting, all with the assistance of ChatGPT.

## Table of Contents

- [Prerequisites](#prerequisites)
- [Getting Started](#getting-started)
- [Usage](#usage)
- [Functions](#functions)
- [License](#license)

## Prerequisites

Before you can use this project, ensure that you have the following prerequisites in place:

- **OpenAI API Key**: You'll need an OpenAI API key to authenticate and interact with the ChatGPT model. You can obtain one from the [OpenAI website](https://beta.openai.com/signup/).

- **Python Environment**: This project is built using Python and requires the following libraries:
  - `openai`: To make API requests to ChatGPT.
  - Other standard libraries used for user input, processing, and formatting.

## Getting Started

1. Clone this repository to your local machine:

   ```bash
   git clone https://github.com/FrankCJones/ArticleWriter/
   ```

2. Navigate to the project directory:

   ```bash
   cd article-generation-with-chatgpt
   ```

3. Set up your OpenAI API key in the Jupyter Notebook by replacing `api_key = None` with your API key:

   ```python
   api_key = "your-api-key-here"
   ```

4. Install the required Python libraries if you haven't already. You can use `pip` to install them:

   ```bash
   pip install openai
   ```

## Usage

To use this project to generate articles, follow these steps:

1. Run the Jupyter Notebook provided in the project directory.

2. In the notebook, you can call the `article_writer(topic)` function with your desired topic or keyword as an argument. This function will generate an article draft for you.

3. Follow the prompts in the notebook to provide a topic or keyword, and the article draft will be displayed.

4. Customize and edit the generated article as needed. You can also adjust the article outline, keywords, and HTML formatting functions as per your requirements.

## Functions

- `article_outline(topic)`: Generates section titles for an article based on the provided topic.

- `article_keyword(topic)`: Generates a list of related keywords for the provided topic.

- `html_format(article_content)`: Formats the provided article content in HTML.

- `article_writer(topic)`: Orchestrates the entire process by calling the above functions and generating a draft article.

## License

This project is licensed under the [MIT License](LICENSE).
