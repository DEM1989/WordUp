
# WordUp: An AI-Powered Word Processor
WordUp is an open-source, PyQt5-based word processor application with AI assistant features powered by OpenAI's GPT models. It's a cross-platform application that can be run on Windows, Mac, and Linux.


## Unleash Your Writing Potential

**WordUp empowers you to:**

* **Craft Compelling Content:**  Effortlessly generate ideas, improve your writing style, and produce high-quality documents.
* **Boost Productivity:**  Automate tedious tasks like summarizing text, expanding on ideas, and conducting research – all within the app.
* **Write with Confidence:**  Get instant feedback on grammar, tone, and clarity, ensuring your writing is polished and professional.

## Table of Contents

1. [Features](#features)
2. [Requirements](#requirements)
3. [Installation and Usage](#installation-and-usage)
4. [Customizing](#customizing)
5. [Contributing](#contributing)
6. [Improvements](#improvements)
7. [Testing](#testing)
8. [License](#license)

## Features


* **AI-Powered Assistant:**
    * **Text Generation & Editing:** Generate creative content, rewrite paragraphs, and get suggestions for improved phrasing.
    * **Summarization & Expansion:** Condense lengthy text into key points or expand on existing ideas with ease.
    * **Research & Information Retrieval:** Search the web and retrieve relevant information directly within WordUp.
* **Rich Text Editing:** Format your documents with headings, lists, bold, italics, and more. 
* **Image Integration:** Easily insert images into your documents. 
* **File Support:** Open and save files in .docx and .txt formats.
* **Customizable Interface:**  Choose between light and dark themes to personalize your writing experience.

## Requirements

- Python 3.6 or higher
- PyQt5
- Pyphen
- python-docx
- BeautifulSoup4
- OpenAI API key

## Installation and Usage
## Getting Started

1. **Installation:**
   - **Prerequisites:** Python 3.6+, OpenAI API Key ([https://platform.openai.com/account/api-keys](https://platform.openai.com/account/api-keys))
  
 Obtain an OpenAI API key and save it in a file called `api_key.json` in the following format:
```json
{
  "api_key": "YOUR_API_KEY"
}
```
Note this first step can be skipped as when the main.py is loaded for the first time it will ask you for an API key

2. Install the required dependencies by running the following command:
```bash
pip install pyqt5 pyphen python-docx beautifulsoup4 openai
```
3. Clone this repository and navigate into it.
4. Run the application using the following command:
```bash
python main.py
```
5. Type text into the main editor window.
6. Highlight text and right click to access assistant features.

Use the toolbar and menu bar options for additional features. Chat with the docked AI assistant widget for help.

## Customizing

The AI assistant capabilities can be customized by modifying the `openai_chat` and `openai_chat2` functions.

Web searching can be configured by adding API keys and modifying the `internet_search` functions.


## Contributing

We welcome contributions to make WordUp even better!

* **Found a bug?** Open an issue on our [issue tracker](https://github.com/your-username/WordUp/issues).
* **Have a feature request?** Suggest it on our [issue tracker](https://github.com/your-username/WordUp/issues).
* **Want to contribute code?** Fork the repository and submit a pull request!

Please follow our [contributing guidelines](https://github.com/your-username/WordUp/blob/main/CONTRIBUTING.md) when making a contribution.


## Improvements

Here are some ideas for improvements:

- Add more assistant features
- Improve web searching
- Optimize performance
- Enhance formatting options
- Support exporting to additional formats

## Testing

To test the application, simply run the application and try out the various features. Automated tests are currently in development.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.


## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details. 
```
