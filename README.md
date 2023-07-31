# PyWord
Open source Word Editor with AI Co-pilot


This is a word processor application built with PyQt5 that provides advanced writing assistance through integration with the OpenAI API.

Features
Rich text editing with formatting options like bold, italic, underline, etc.
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
Python 3.6+
PyQt5
OpenAI API key
python-docx
BeautifulSoup4
Requests
Transformers
Spellchecker
Pyphen
Usage
Clone the repository
Install dependencies with pip install -r requirements.txt
Sign up for an OpenAI API key at https://openai.com/api/ and add it to the code
Run python wordeditor.py to start the application
The assistant panel provides advanced writing aids - simply select some text and use the context menu to access relevant features. The internet search capability leverages Wikipedia, DuckDuckGo and OpenAI's summary abilities to provide informed responses.

Please refer to the source code for additional details on implementation.

Limitations
Large documents can slow down performance due to repeated calls to the OpenAI API
Internet searches may fail if Wikipedia/DuckDuckGo change their API
The full functionality requires a paid OpenAI API key
Contributions to improve the application are welcome!
