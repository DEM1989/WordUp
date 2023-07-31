# WordUp

WordUp is an open-source, PyQt5-based word processor application with AI assistant features powered by OpenAI's GPT models. It's a cross-platform application that can be run on Windows, Mac, and Linux.

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

- Rich text editing with formatting options (bold, italic, underline, etc.)
- Insert images
- Zoom in/out
- Spell checking
- Word count tracking
- Assistant panel powered by GPT-3.5 and GPT-4 that provides:
    - Text analysis
    - Grammar assessment
    - Idea generation
    - Text extension/summarization
    - Contextual autocomplete suggestions
    - Internet research capabilities
- Support for .docx and .txt files
- Find/replace text
- Image insertion
- Zooming
- Print preview
- Customizable settings
- Light and dark themes
- Generated image view and saving

## Requirements

- Python 3.6 or higher
- PyQt5
- Pyphen
- python-docx
- BeautifulSoup4
- OpenAI API key

## Installation and Usage

1. Obtain an OpenAI API key and save it in a file called `api_key.json` in the following format:
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

Contributions to add features or fix bugs are welcome! Please open an issue or submit a pull request. When submitting a pull request, please ensure that your changes do not break existing functionality and include tests for new features or bug fixes.

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