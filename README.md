# WordUp
Open source Word Editor with AI Co-pilot


Wordup is a PyQt5-based word processor application with AI assistant features powered by OpenAI's GPT models. It is a cross-platform application that can be run on Windows, Mac, and Linux.

Features

Rich text editing with formatting options (bold, italic, underline, etc.)
Insert images
Zoom in/out
Spell checking
Word count tracking
Assistant panel powered by GPT-3.5 that provides:
Text analysis
Grammar assessment
Idea generation
Text extension/summarization
Contextual autocomplete suggestions
Internet research capabilities
Support for .docx and .txt files
Find/replace text
Image insertion
Zooming
Print preview
Customizable settings
Light and dark themes
Generated image view and saving
Requirements

Python 3.6 or higher
PyQt5
Pyphen
python-docx
BeautifulSoup4
OpenAI API key
Usage

1. Obtain an OpenAI API key and save it in a file called api_key.json in the following format:
{
  "api_key": "YOUR_API_KEY"
}

2. Install dependencies:
pip install pyqt5 pyphen python-docx beautifulsoup4 openai

3. Run the application:
python main.py

4. Type text into the main editor window.

5. Highlight text and right click to access assistant features.

Use the toolbar and menu bar options for additional features. Chat with the docked AI assistant widget for help.

Customizing

The AI assistant capabilities can be customized by modifying the openai_chat and openai_chat2 functions.

Web searching can be configured by adding API keys and modifying the internet_search functions.

Contributing

Contributions to add features or fix bugs are welcome! Please open an issue or submit a pull request.

Some ideas for improvements:

Add more assistant features
Improve web searching
Optimize performance
Enhance formatting options
Support exporting to additional formats

Some ideas for improvements:

Add more assistant features
Improve web searching
Optimize performance
Enhance formatting options
Support exporting to additional formats
License

This project is licensed under the MIT License - see the LICENSE file for details.