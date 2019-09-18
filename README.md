# Audio Python
A Python script using gTTS library to create Text-To-Speech mp3 - https://letslearnabout.net/python/creating-text-to-speech-with-python-and-gtts/

## Requirements 
You only need to create a virtual environment and install gtts with "pip install gtts". Or use the requirements.txt.

### How it works
This projects creates an mp3 from text (Text-to-speech). This text can be provided using one of the 3 ways provided in the script:

reading_from_string() - Creates an mp3 from the _text_to_read_ variable.

reading_from_user() - Prompts the user to enter an input. That text will be the one used to create the mp3.

reading_from_file() - Promptes the user to enter the name of the file. Then, appends _.txt_, reds the file, extracts the text and creates the mp3.

Switch around any of the 3 ways by replacing the call to the method used at the bottom of the code.
